load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "net",
    srcs = [
        "ipfamily.go",
        "ipnet.go",
        "multi_listen.go",
        "net.go",
        "parse.go",
        "port.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/utils/net",
    importpath = "k8s.io/utils/net",
    visibility = ["//visibility:public"],
    deps = ["//vendor/k8s.io/utils/internal/third_party/forked/golang/net"],
)
