load("@bazel_tools//tools/build_defs/pkg:pkg.bzl", "pkg_tar")

pkg_tar(
    name = "pkg",
    srcs = glob([
        "config/*",
        "constraints/*",
        "host_config/*",
        "platforms/*",
        "host_constraints/*",
        "host_platforms/*",
        "*.bzl",
        "BUILD*",
        "*.tpl",
    ]),
    extension = "tar.gz",
    mode = "0644",
    strip_prefix = ".",
)