load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "discovery",
    srcs = [
        "doc.go",
        "generated.pb.go",
        "register.go",
        "types.go",
        "types_swagger_doc_generated.go",
        "well_known_labels.go",
        "zz_generated.deepcopy.go",
        "zz_generated.prerelease-lifecycle.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/api/discovery/v1",
    importpath = "k8s.io/api/discovery/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/gogo/protobuf/proto",
        "//vendor/github.com/gogo/protobuf/sortkeys",
        "//vendor/k8s.io/api/core/v1:core",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
    ],
)
