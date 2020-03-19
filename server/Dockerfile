FROM golang:1.12

ENV GO111MODULE=off

WORKDIR /go/src/grpc-web-react-go/server
COPY . .
RUN go get github.com/pilu/fresh
CMD ["fresh"]
EXPOSE 9090