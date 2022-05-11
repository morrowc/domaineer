all: proto proto_go

proto: *.proto
	/usr/bin/protoc --proto_path=. --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative domaineer.proto

proto_go: *.proto
	/usr/bin/protoc --proto_path=. --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative domaineer.proto

