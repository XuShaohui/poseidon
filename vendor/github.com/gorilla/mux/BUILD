load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "context_gorilla.go",
        "context_native.go",
        "doc.go",
        "middleware.go",
        "mux.go",
        "regexp.go",
        "route.go",
        "test_helpers.go",
    ],
    importpath = "github.com/gorilla/mux",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/gorilla/context:go_default_library"],
)
