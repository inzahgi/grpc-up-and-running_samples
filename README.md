
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



### ch3
#### order-service-client
> protoc --java_out=.\ch3\client\src\main\java --proto_path=.\ch3\client\src\main\resources\proto .\ch3\client\src\main\resources\proto\order_management.proto

> protoc --plugin=protoc-gen-grpc-java=e:\proto\protoc-gen-grpc-java-1.50.2-windows-x86_64.exe --grpc-java_out=.\ch3\client\src\main\java\ --proto_path=.\ch3\client\src\main\resources\proto .\ch3\client\src\main\resources\proto\order_management.proto

#### order-service-client
> protoc --java_out=.\ch3\server\src\main\java --proto_path=.\ch3\server\src\main\resources\proto .\ch3\server\src\main\resources\proto\order_management.proto

> protoc --plugin=protoc-gen-grpc-java=e:\proto\protoc-gen-grpc-java-1.50.2-windows-x86_64.exe --grpc-java_out=.\ch3\server\src\main\java\ --proto_path=.\ch3\server\src\main\resources\proto .\ch3\server\src\main\resources\proto\order_management.proto


### ch5

cancellation
#### cancellation -> ch5-cancellation-client
> protoc --java_out=.\ch5\cancellation\ch5-cancellation-client\src\main\java --proto_path=.\ch5\cancellation\ch5-cancellation-client\src\main\resources\proto .\ch5\cancellation\ch5-cancellation-client\src\main\resources\proto\order_management.proto

> protoc --plugin=protoc-gen-grpc-java=e:\proto\protoc-gen-grpc-java-1.50.2-windows-x86_64.exe --grpc-java_out=.\ch5\cancellation\ch5-cancellation-client\src\main\java\ --proto_path=.\ch5\cancellation\ch5-cancellation-client\src\main\resources\proto .\ch5\cancellation\ch5-cancellation-client\src\main\resources\proto\order_management.proto

##### cancellation -> ch5-cancellation-server
> protoc --java_out=.\ch5\cancellation\ch5-cancellation-server\src\main\java --proto_path=.\ch5\cancellation\ch5-cancellation-server\src\main\resources\proto .\ch5\cancellation\ch5-cancellation-server\src\main\resources\proto\order_management.proto

> protoc --plugin=protoc-gen-grpc-java=e:\proto\protoc-gen-grpc-java-1.50.2-windows-x86_64.exe --grpc-java_out=.\ch5\cancellation\ch5-cancellation-server\src\main\java\ --proto_path=.\ch5\cancellation\ch5-cancellation-server\src\main\resources\proto .\ch5\cancellation\ch5-cancellation-server\src\main\resources\proto\order_management.proto


compression
#### compression -> ch5-compression-client
> protoc --java_out=.\ch5\compression\ch5-compression-client\src\main\java --proto_path=.\ch5\compression\ch5-compression-client\src\main\resources\proto .\ch5\compression\ch5-compression-client\src\main\resources\proto\order_management.proto

> protoc --plugin=protoc-gen-grpc-java=e:\proto\protoc-gen-grpc-java-1.50.2-windows-x86_64.exe --grpc-java_out=.\ch5\compression\ch5-compression-client\src\main\java\ --proto_path=.\ch5\compression\ch5-compression-client\src\main\resources\proto .\ch5\compression\ch5-compression-client\src\main\resources\proto\order_management.proto

##### compression -> ch5-compression-server
> protoc --java_out=.\ch5\compression\ch5-compression-server\src\main\java --proto_path=.\ch5\compression\ch5-compression-server\src\main\resources\proto .\ch5\compression\ch5-compression-server\src\main\resources\proto\order_management.proto

> protoc --plugin=protoc-gen-grpc-java=e:\proto\protoc-gen-grpc-java-1.50.2-windows-x86_64.exe --grpc-java_out=.\ch5\compression\ch5-compression-server\src\main\java\ --proto_path=.\ch5\compression\ch5-compression-server\src\main\resources\proto .\ch5\compression\ch5-compression-server\src\main\resources\proto\order_management.proto


deadlines
#### deadlines -> ch5-deadlines-client
> protoc --java_out=.\ch5\deadlines\ch5-deadlines-client\src\main\java --proto_path=.\ch5\deadlines\ch5-deadlines-client\src\main\resources\proto .\ch5\deadlines\ch5-deadlines-client\src\main\resources\proto\order_management.proto

> protoc --plugin=protoc-gen-grpc-java=e:\proto\protoc-gen-grpc-java-1.50.2-windows-x86_64.exe --grpc-java_out=.\ch5\deadlines\ch5-deadlines-client\src\main\java\ --proto_path=.\ch5\deadlines\ch5-deadlines-client\src\main\resources\proto .\ch5\deadlines\ch5-deadlines-client\src\main\resources\proto\order_management.proto

##### deadlines -> ch5-deadlines-server
> protoc --java_out=.\ch5\deadlines\ch5-deadlines-server\src\main\java --proto_path=.\ch5\deadlines\ch5-deadlines-server\src\main\resources\proto .\ch5\deadlines\ch5-deadlines-server\src\main\resources\proto\order_management.proto

> protoc --plugin=protoc-gen-grpc-java=e:\proto\protoc-gen-grpc-java-1.50.2-windows-x86_64.exe --grpc-java_out=.\ch5\deadlines\ch5-deadlines-server\src\main\java\ --proto_path=.\ch5\deadlines\ch5-deadlines-server\src\main\resources\proto .\ch5\deadlines\ch5-deadlines-server\src\main\resources\proto\order_management.proto



error-handing
#### error-handing -> ch5-error-handing-client
> protoc --java_out=.\ch5\error-handing\ch5-error-handing-client\src\main\java --proto_path=.\ch5\error-handing\ch5-error-handing-client\src\main\resources\proto .\ch5\error-handing\ch5-error-handing-client\src\main\resources\proto\order_management.proto

> protoc --plugin=protoc-gen-grpc-java=e:\proto\protoc-gen-grpc-java-1.50.2-windows-x86_64.exe --grpc-java_out=.\ch5\error-handing\ch5-error-handing-client\src\main\java\ --proto_path=.\ch5\error-handing\ch5-error-handing-client\src\main\resources\proto .\ch5\error-handing\ch5-error-handing-client\src\main\resources\proto\order_management.proto

##### error-handing -> ch5-error-handing-server
> protoc --java_out=.\ch5\error-handing\ch5-error-handing-server\src\main\java --proto_path=.\ch5\error-handing\ch5-error-handing-server\src\main\resources\proto .\ch5\error-handing\ch5-error-handing-server\src\main\resources\proto\order_management.proto

> protoc --plugin=protoc-gen-grpc-java=e:\proto\protoc-gen-grpc-java-1.50.2-windows-x86_64.exe --grpc-java_out=.\ch5\error-handing\ch5-error-handing-server\src\main\java\ --proto_path=.\ch5\error-handing\ch5-error-handing-server\src\main\resources\proto .\ch5\error-handing\ch5-error-handing-server\src\main\resources\proto\order_management.proto

