load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["tpu-gen.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/api/tpu/v1",
    importpath = "google.golang.org/api/tpu/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/google.golang.org/api/gensupport:go_default_library",
        "//vendor/google.golang.org/api/googleapi:go_default_library",
    ],
)
