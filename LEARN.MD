# gRPC in Spring Boot Learn Note

---

## gRPC in Spring Boot Learn Note

### Step.1 Install Dependencies

### Step.2 Write proto file

### Step.3 Compile proto 

#### Before compile proto file, you need to install protoc compiler

[Download Protoc Compiler](https://github.com/protocolbuffers/protobuf/releases)

Don,t forget add it to your OS PATH

#### Compile proto file


[Install Protoc Gen Java](https://repo1.maven.org/maven2/io/grpc/protoc-gen-grpc-java/1.59.1/)
```shell
mvn protobuf:compile
```

### Step.4 Write Service

### Step.5 Write Controller