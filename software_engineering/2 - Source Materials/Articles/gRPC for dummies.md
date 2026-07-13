#### What it is

gRPC is a communication protocol developed by Google.
It is important to know that gRPC is the Googles implementation of the RPC specification, there are other implementations developed by other companies.

Some key distinctions in the RPC protocol is requests from clients to servers are done with method calls that look like a function call in most programming languages (i.e it looks like you are calling a function in-code) as opposed to other protocols like HTTP that have predefined methods GET, POST etc that have bespoke responsibilities in a client/server exchange.

Also, RPC uses thrift or protobuf to encode messages transmitted between clients and servers. protobuf/thrift encodes messages in non human-readable format

Remote Procedure Call (RPC) means calling a function defined on a remote instance (server etc)

#### How does it work?

![[Excalidraw/How-RPC-Works.excalidraw]]

The stubs are majorly responsible for marshalling parameters to be sent to the server and un-marshalling server responses returned to clients.

___
###### Material Source
https://medium.com/@sourabh1024/grpc-for-dummies-9569193ad3e5
