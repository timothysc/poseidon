load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "handlers.go",
        "stats.go",
    ],
    importmap = "github.com/kubernetes-sigs/poseidon/vendor/google.golang.org/grpc/stats",
    importpath = "google.golang.org/grpc/stats",
    visibility = ["//visibility:public"],
    deps = ["//vendor/golang.org/x/net/context:go_default_library"],
)
