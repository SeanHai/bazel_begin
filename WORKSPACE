load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository" )

new_git_repository(
    name = "com_google_googletest",
    build_file = "bazel/gmock.BUILD",
    remote = "https://github.com/google/googletest",
    tag = "release-1.8.0",
)

bind(
    name = "gtest",
    actual = "@com_google_googletest//:gtest",
)
