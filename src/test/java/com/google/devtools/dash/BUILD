java_library(
    name = "util",
    srcs = ["ProtoInputStream.java"],
    deps = [
        "//external:javax/servlet/api",
        "@bazel_tools//third_party:protobuf",
    ],
)

java_test(
    name = "dash",
    srcs = [
        "DashRequestTest.java",
    ],
    deps = [
        "@com_google_appengine_java//:jars",
        "@easymock//jar",
        ":util",
        "//src/main/java:servlets",
        "//src/main/protobuf:proto_dash",
        "@bazel_tools//third_party:junit4",
        "@bazel_tools//third_party:truth",
    ],
)
