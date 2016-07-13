load("//tools/build_rules:custom_proto.bzl", "go_proto_library")

go_proto_library(
  name = "sad",
  srcs = ["sad.proto"],
  protoc_gen_go = "@go_protobuf//:protoc-gen-go-bin",
  go_libs = ["@go_protobuf//:proto"],
)
