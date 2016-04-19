java_library(
    name = "util",
    srcs = ["ProtoInputStream.java"],
    deps = [
        "@io_bazel//third_party/protobuf",
        "@io_bazel_rules_appengine//appengine:javax.servlet.api",
    ],
)

java_test(
    name = "DashRequestTest",
    srcs = [
        "DashRequestTest.java",
    ],
    deps = [
        "@io_bazel//third_party:junit4",
        "@io_bazel//third_party:truth",
        "@com_google_appengine_java//:jars",
        "@easymock//jar",
        ":util",
        "//src/main/java:servlets",
        "//src/main/protobuf:proto_dash",
    ],
)
