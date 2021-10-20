# protos-grpc-helpers

Public repo to protobufs


## Instalaciones necesarias:

```bash
#Golang dependencies
> go get google.golang.org/grpc
> go get -u google.golang.org/grpc
> go get google.golang.org/grpc/cmd/protoc-gen-go-grpc
> go get google.golang.org/protobuf/cmd/protoc-gen-go

#Compilar archivo .proto
> protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative <.proto filename path>
```