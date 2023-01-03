
# java code 

the resource repository of the book "gRPC - Up and Running". 
It is maven project for java.
I use windows 10 operation system and jdk 1.8.



## Building


protoc-gen-grpc-java-1.50.2-windows-x86_64.exe
add path 

### ch2
#### client
> protoc --java_out=.\ch2\client\src\main\java --proto_path=.\ch2\client\src\main\resources\proto .\ch2\client\src\main\resources\proto\product_info.proto

> protoc --plugin=protoc-gen-grpc-java=e:\proto\protoc-gen-grpc-java-1.50.2-windows-x86_64.exe --grpc-java_out=.\ch2\client\src\main\java\ --proto_path=.\ch2\client\src\main\resources\proto .\ch2\client\src\main\resources\proto\product_info.proto


#### server
> protoc --java_out=.\ch2\server\src\main\java --proto_path=.\ch2\server\src\main\resources\proto .\ch2\server\src\main\resources\proto\product_info.proto

> protoc --plugin=protoc-gen-grpc-java=e:\proto\protoc-gen-grpc-java-1.50.2-windows-x86_64.exe --grpc-java_out=.\ch2\server\src\main\java\ --proto_path=.\ch2\server\src\main\resources\proto .\ch2\server\src\main\resources\proto\product_info.proto




