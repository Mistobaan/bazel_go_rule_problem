#git_repository(
#    name = "io_bazel_rules_go",
#    remote = "https://github.com/bazelbuild/rules_go.git",
#    tag = "0.0.3",
#)

local_repository(
  name = "io_bazel_rules_go",
  path = "/Users/fmilo/workspace/funplayground/rules_go"
)

load("@io_bazel_rules_go//go:def.bzl", "go_repositories")

go_repositories()

git_repository(
  name = "protobuf",
  remote = "https://github.com/google/protobuf",
  commit = "b1b9c25"
)

bind(
  name = "protoc",
  actual = "@protobuf//:protoc"
)

new_git_repository(
  name = "go_protobuf",
  remote = "https://github.com/golang/protobuf",
  commit = "68415e7",
  build_file = "tools/build_rules/BUILD.go-protobuf",
)
