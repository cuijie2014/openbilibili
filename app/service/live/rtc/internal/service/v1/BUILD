package(default_visibility = ["//visibility:public"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = ["rtc.go"],
    importpath = "go-common/app/service/live/rtc/internal/service/v1",
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
    deps = [
        "//app/service/live/rtc/api/v1:go_default_library",
        "//app/service/live/rtc/internal/conf:go_default_library",
        "//app/service/live/rtc/internal/dao:go_default_library",
        "//app/service/live/rtc/internal/model:go_default_library",
        "//app/service/live/rtc/internal/service:go_default_library",
        "//library/cache/redis:go_default_library",
        "//library/log:go_default_library",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
