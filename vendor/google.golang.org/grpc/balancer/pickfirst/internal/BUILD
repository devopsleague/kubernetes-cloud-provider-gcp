load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "internal",
    srcs = ["internal.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/balancer/pickfirst/internal",
    importpath = "google.golang.org/grpc/balancer/pickfirst/internal",
    visibility = ["//vendor/google.golang.org/grpc/balancer/pickfirst:__subpackages__"],
)
