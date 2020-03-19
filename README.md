# grpc-web
applicarion using grpc-web
# Step1 install
install go plugin
```
$ go get -u google.golang.org/grpc
```
```
$ go get -u github.com/golang/protobuf/protoc-gen-go
```
```
$ export PATH=$PATH:$GOPATH/bin
```
# Step2 start client
```
$ cd client
```
```
$ yarn start
```
# Step3 start
```
$ docker-compose up -d server proxy client
```
