FROM golang:1.21.3

RUN mkdir /app
WORKDIR /app

ADD . /app
RUN go install ./...

CMD /go/bin/greeter_server
