workspace(name = "hive")

http_archive(
    name = "io_bazel_rules_go",
    sha256 = "0f6c9f6ddc9b69f0f51c74d8a7b7fcf6aad0b1f8c8e9f9b2eeb0651686c5f5e5",
    strip_prefix = "rules_go-2.1.0",
    url = "https://github.com/bazelbuild/rules_go/releases/download/2.1.0/rules_go-2.1.0.tar.gz",
)

load("@io_bazel_rules_go//go:deps.bzl", "go_register_toolchains", "go_rules_dependencies")

go_rules_dependencies()

go_register_toolchains()
