# @generated: This file was generated by bzl. Do not modify!
# Argument overrides and custom targets should be specified in BUILD.in.

load("//build_tools/go:go.bzl", "dbx_go_library")

dbx_go_library(
    name = "box",
    srcs = [
        "box.go",
    ],
    visibility = [
        "//go/src:__subpackages__",
    ],
    deps = [
        "//go/src/golang.org/x/crypto/curve25519",
        "//go/src/golang.org/x/crypto/nacl/secretbox",
        "//go/src/golang.org/x/crypto/salsa20/salsa",
    ],
)
