load("//tools:build_rules/go.bzl", "go_release_binary")

package(default_visibility = ["//kythe:default_visibility"])

go_release_binary(
    name = "dedup_stream",
    srcs = ["dedup_stream.go"],
    deps = [
        "//kythe/go/platform/delimited",
        "//kythe/go/platform/delimited/dedup",
        "//kythe/go/util/datasize",
        "//kythe/go/util/flagutil",
    ],
)
