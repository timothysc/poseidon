load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "avgvar.go",
        "iterator.go",
        "llrb.go",
        "llrb-stats.go",
        "util.go",
    ],
    importmap = "github.com/kubernetes-sigs/poseidon/vendor/github.com/petar/GoLLRB/llrb",
    importpath = "github.com/petar/GoLLRB/llrb",
    visibility = ["//visibility:public"],
)
