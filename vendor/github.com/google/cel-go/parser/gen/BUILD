load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "gen",
    srcs = [
        "cel_base_listener.go",
        "cel_base_visitor.go",
        "cel_lexer.go",
        "cel_listener.go",
        "cel_parser.go",
        "cel_visitor.go",
        "doc.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/google/cel-go/parser/gen",
    importpath = "github.com/google/cel-go/parser/gen",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/antlr4-go/antlr/v4:antlr"],
)
