
#### gRPC communication patterns

- Unary (one-to-one) : Client sends one request, server sends one response 
- Server streaming (one-to-many) : client sends one request, server streams multiple responses
- Client streaming (many-to-one) : client sends multiple requests and server sends one response
- Bidirectional streaming (many-to-many) : both client/server sends messages in real time / same time

#### Protocol Buffers (Protobuf)
Protobuf is an IDL (Interface Definition Language) tool useful for describing the structure of messages to be transmitted in a gRPC request-response cycle.

Protobuf does not just describe the structure of messages, it also defines and describes the service interfaces of the remote procedures to be executed/called.

The Protobuf tool serialises structured data into binary so it can be compact and easily sent over the network, then also deserialises the data back to its structured format to be stored for used for computation.

---
###### Material Source
https://medium.com/@sachinsoni600517/a-beginners-guide-to-grpc-what-it-is-and-why-you-should-use-it-e3bb4d93d7fe