# gRPC Book API

// generate book.pb.go (serializing messages using protobuf) and book_grpc_pb.go (grpc client and server code)
// protoc ./api/v1/\*.proto --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative --proto_path=.
