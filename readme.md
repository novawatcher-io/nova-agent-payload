
后面需要写Makefile,暂时使用命令行生成，node 物理机上报指标:

```
protoc --go_out=. --go_opt=paths=source_relative     --go-grpc_out=. --go-grpc_opt=paths=source_relative     node/v1/info.proto
```

