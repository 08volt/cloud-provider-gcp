load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "metadata",
    srcs = ["metadata.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/metadata",
    importpath = "google.golang.org/grpc/metadata",
    visibility = ["//visibility:public"],
    deps = ["//vendor/google.golang.org/grpc/internal"],
)
