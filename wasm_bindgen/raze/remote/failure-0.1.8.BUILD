"""
@generated
cargo-raze crate build file.

DO NOT EDIT! Replaced on runs of cargo-raze
"""

# buildifier: disable=load
load(
    "@io_bazel_rules_rust//rust:rust.bzl",
    "rust_binary",
    "rust_library",
    "rust_test",
)

# buildifier: disable=load
load("@bazel_skylib//lib:selects.bzl", "selects")

package(default_visibility = [
    # Public for visibility by "@raze__crate__version//" targets.
    #
    # Prefer access through "//wasm_bindgen/raze", which limits external
    # visibility to explicit Cargo.toml dependencies.
    "//visibility:public",
])

licenses([
    "notice",  # MIT from expression "MIT OR Apache-2.0"
])

# Generated targets
# Unsupported target "bail_ensure" with type "example" omitted
# Unsupported target "basic_fail" with type "test" omitted
# Unsupported target "error_as_cause" with type "example" omitted
# Unsupported target "fail_compat" with type "test" omitted

# buildifier: leave-alone
rust_library(
    name = "failure",
    crate_type = "lib",
    deps = [
        "@rules_rust_wasm_bindgen__backtrace__0_3_53//:backtrace",
    ],
    srcs = glob(["**/*.rs"]),
    crate_root = "src/lib.rs",
    edition = "2015",
    proc_macro_deps = [
        "@rules_rust_wasm_bindgen__failure_derive__0_1_8//:failure_derive",
    ],
    rustc_flags = [
        "--cap-lints=allow",
    ],
    version = "0.1.8",
    tags = [
        "cargo-raze",
        "manual",
    ],
    crate_features = [
        "backtrace",
        "default",
        "derive",
        "failure_derive",
        "std",
    ],
)
# Unsupported target "macro_trailing_comma" with type "test" omitted
# Unsupported target "simple" with type "example" omitted
# Unsupported target "string_custom_error_pattern" with type "example" omitted
