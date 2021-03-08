FROM randomdude/gcc-cross-x86_64-elf

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y g++
RUN apt-get install -y binutils
RUN apt-get install -y libc6-dev-i386
RUN apt-get install -y grub-legacy
RUN apt-get install -y xorriso

VOLUME /root/env
WORKDIR /root/env

