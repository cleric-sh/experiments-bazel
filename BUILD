package(default_visibility = ["//visibility:public"])

# load("@npm//@bazel/typescript:index.bzl", "ts_config")

# filegroup(
#     name = "config",
#     srcs = [
#         "package.json",
#         "yarn.lock"        
#     ]
# )

# ts_config(
#     name = "ts_config",
#     src = "tsconfig.json"
# )

exports_files([
    "tsconfig.json",
    "package.json",
    "readme.md",
    "version.bzl",
])

# load("//tools:ts_library.bzl", "ts_library")

# # TODO: This is only here in order to workaround a bug in the way bazel resolves
# # workspace imports when in nested repositories, and can be removed once that is fixed.
# ts_library(
#     name = "modules-fix",
#     srcs = [],
#     module_name = "@cleric",
# )
