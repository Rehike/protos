# Deprecation notice

The content of this repository has been moved to [src/protos in the main repository.](//github.com/Rehike/Rehike/tree/master/src/protos)

# Protos

This repository contains Protobuf definitions that Rehike uses including but not limited to reverse engineered InnerTube Protobuf formats.

In order to use these in Rehike, you must first compile these to PHP with [protoc](https://grpc.io/docs/protoc-installation/) and then dump the result into Rehike's `modules/generated` folder.

```
protoc --proto_path=/path/to/protos --php_out=out/php /path/to/protos/*.proto
```
