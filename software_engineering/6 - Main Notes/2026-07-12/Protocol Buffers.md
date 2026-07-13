2026-07-12 14:03

Status: #baby 

Tags: [[grpc]] [[rpc]]

## Protobuf

A key distinction between gRPC and other RPC implementations is that gRPC primarily supports the use of Protocol Buffers or Protobuf for short for specifying/defining the structures of the RPC services supported by the gRPC server including details of methods/procedures exposed by the service and the input/response types/messages of the said methods.

gRPC supports other tools but protobuf is the de facto way in gRPC.

The function of the protobuf tool does not end at interface definition, it is also used for marshalling and un-marshalling the defined message payloads into binary which is compact and easier to send over the network.

###### References
[[A Beginner’s Guide to gRPC - What It Is and Why You Should Use It]]
[[gRPC for dummies]]
[[REST vs RPC - What problems are you trying to solve with your APIs?]]
[[grpc Communication patterns]]
[[google Remote Procedure Calls]]