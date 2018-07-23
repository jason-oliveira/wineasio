FROM amd64/ubuntu:14.04

RUN apt-get update && apt-get install -y \
        build-essential

RUN dpkg --add-architecture i386

RUN apt-get update && apt-get install -y \
	wine1.6-dev wine1.6-amd64 wine1.6:i386

RUN apt-get update && apt-get install -y \
	libjack-jackd2-dev

RUN apt-cache search libjack
