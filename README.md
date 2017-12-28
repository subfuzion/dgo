# dgo

All-in-one image currently based on Debian 9 (Stretch) for Go 1.10+ development, including
gRPC, protocol buffers, and gogo/protobuf.

[![Docker Build Status](https://img.shields.io/docker/build/subfuzion/dgo.svg)](subfuzion/dgo)

The image contains:

* [Go 1.10](https://tip.golang.org/doc/go1.10)
* [Protocol Buffers 3.5.1](https://github.com/google/protobuf/releases/tag/v3.5.1)
* [gogo/protobuf](https://github.com/gogo/protobuf)
* [gRPC](https://github.com/grpc/grpc-go)
* [grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway/)
* [dep](https://github.com/golang/dep)
* [gometalinter](https://github.com/alecthomas/gometalinter)
* Miscellaneous (apt-utils, build-essential, autoconf/automake, etc -- see Dockerfile)

