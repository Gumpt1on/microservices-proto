protoc -I ./order --go_out ./golang/order --go_opt paths=source_relative --go-grpc_out ./golang/order --go-grpc_opt paths=source_relative ./order/order.proto

protoc -I ./payment --go_out ./golang/payment --go_opt paths=source_relative --go-grpc_out ./golang/payment --go-grpc_opt paths=source_relative ./payment/payment.proto

protoc -I ./shipping --go_out ./golang/shipping --go_opt paths=source_relative --go-grpc_out ./golang/shipping --go-grpc_opt paths=source_relative ./shipping/shipping.proto

module github.com/Gumpt1on/microservices-proto/golang/payment

module github.com/Gumpt1on/microservices-proto/golang/shipping