load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "global",
    srcs = [
        "handler.go",
        "instruments.go",
        "internal_logging.go",
        "meter.go",
        "propagator.go",
        "state.go",
        "trace.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/go.opentelemetry.io/otel/internal/global",
    importpath = "go.opentelemetry.io/otel/internal/global",
    visibility = ["//vendor/go.opentelemetry.io/otel:__subpackages__"],
    deps = [
        "//vendor/github.com/go-logr/logr",
        "//vendor/github.com/go-logr/stdr",
        "//vendor/go.opentelemetry.io/auto/sdk",
        "//vendor/go.opentelemetry.io/otel/attribute",
        "//vendor/go.opentelemetry.io/otel/codes",
        "//vendor/go.opentelemetry.io/otel/metric",
        "//vendor/go.opentelemetry.io/otel/metric/embedded",
        "//vendor/go.opentelemetry.io/otel/propagation",
        "//vendor/go.opentelemetry.io/otel/trace",
        "//vendor/go.opentelemetry.io/otel/trace/embedded",
    ],
)
