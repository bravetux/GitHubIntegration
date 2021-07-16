FROM gcc:latest

COPY . /usr/src/string

WORKDIR /usr/src/string

RUN make clean; make make main.o

CMD ["main"]
