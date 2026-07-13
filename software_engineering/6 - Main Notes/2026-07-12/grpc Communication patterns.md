2026-07-12 13:58

Status: #child

Tags: [[rpc]] [[grpc]]

## Communication Patterns in gRPC

gRPC supports message streaming and supports different communication patterns between the client and server. The patterns include:
- **Unary pattern** - one-to-one : In the unary pattern, the client sends a single request to the server and the server sends back a single response back to the client.
- **Server streaming pattern** - one-to-many: In the one to many pattern a client sends a single request to the server and the server sends back multiple message streams as responses.
- **Client streaming pattern** - many-to-one: In the many to one pattern the client sends multiple message streams as requests and a server responds in a single stream/response.
- **Bidirectional pattern**: in the bidirectional pattern, both client/server can send messages at the same time to each other in real time.

###### References

[[A Beginner’s Guide to gRPC - What It Is and Why You Should Use It]]
[[gRPC for dummies]]
[[REST vs RPC - What problems are you trying to solve with your APIs?]]
[[Protocol Buffers]]
[[google Remote Procedure Calls]]
