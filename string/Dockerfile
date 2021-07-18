FROM gcc:latest

COPY . /usr/src/string

WORKDIR /usr/src/string
RUN apt-get update && apt-get install -y \
  gcc \
  libc-dev \
  && rm -rf /var/lib/apt/lists/*

RUN make; make main.o

CMD ["./main"]
