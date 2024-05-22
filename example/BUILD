load("@rules_cc//cc:defs.bzl", "cc_binary")

cc_binary(
    name = "hello-world",
    srcs = ["hello-world.cc"],
)
cc_test(
  name = "hello_test",
  size = "small",
  srcs = ["hello_test.cc"],
  deps = ["@com_google_googletest//:gtest_main"],
)
