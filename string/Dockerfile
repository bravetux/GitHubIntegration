FROM gcc:latest

COPY . /usr/src/test

WORKDIR /usr/src/test

RUN gcc -o hello hello.c

CMD ["hello"]