FROM golang:1.16 

WORKDIR /go/src/app
COPY . .
ENTRYPOINT [ "go", "run", "hello.go" ]

FROM alpine:3.13
WORKDIR /go/src/app
ENTRYPOINT [ "go", "run", "hello.go" ]