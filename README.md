# grpc stream

Flutter モバイルアプリからgRPCを使って
位置情報を送信し続けるようにする

- Server streaming RPC
- Client streaming RPC

の実装をする

### generate from protocol buffer

```shell
protoc --proto_path ./idl/proto/ --go_out=plugins=grpc:./server/pb stream.proto
```
