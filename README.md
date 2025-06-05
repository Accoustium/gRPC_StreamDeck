


Run Python gRPC code generation

```shell
python -m grpc_tools.protoc -I .\src\protos --python_out=.\src\pygrpc --pyi_out=.\src\pygrpc --grpc_python_out=.\src\pygrpc .\src\protos\HelloWorld.proto
```