# steps


* create the .proto file
* install the grpcio-tools
* cd recommendations
* python -m grpc_tools.protoc -I ../protobufs --python_out=. --grpc_python_out=. ../protobufs/recommendations.proto