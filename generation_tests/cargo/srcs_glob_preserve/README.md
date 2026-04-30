Test for preserving custom excludes with rust_srcs_glob.

This test verifies that when rust_srcs_glob is enabled and a rust_library
already has a glob exclude list, Gazelle preserves custom excludes while
still applying the generated glob output.
