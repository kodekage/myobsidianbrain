2026-07-12 11:30

Status: #baby

Tags: [[rpc]] [[grpc]]

## gRPC
#### Overview

gRPC was developed by the google engineering team. It is an implementation of the RPC specification that uses Protobuf tool for specifying the services and the messages to be transmitted or stored over the request/response interactions of the gRPC client and server.

gRPC uses HTTP/2 as its transport layer under the hood.
#### Benefits of gRPC

1. **Light Weight Messages**: gRPC thanks to protobuf compiles messages into binary format which makes messages to be transmitted lighter than other message formats like JSON.
2. **Procedure Methods**: gRPC mirrors every day functions used in programming, so there aren't much overhead in defining a procedure as compared to other communication protocol where you have to define methods and method handlers e.g HTTP APIs
3. **Streaming**: gRPC provides multiple communication patterns like server streaming, client streaming, bidirectional streaming etc all in one protocol, while restful http apis typically just support unary communication pattern (request-response/ono-to-one)

###### References
[[A Beginner’s Guide to gRPC - What It Is and Why You Should Use It]]
[[gRPC for dummies]]
[[REST vs RPC - What problems are you trying to solve with your APIs?]]
[[grpc Communication patterns]]
[[Protocol Buffers]]

