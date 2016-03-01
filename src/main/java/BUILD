java_binary(
    name = "java-bin",
    main_class = "does.not.exist",
    visibility = ["//:__pkg__"],
    runtime_deps = [":servlets"],
)

java_library(
    name = "servlets",
    srcs = glob(["**/*.java"]),
    visibility = ["//src/test/java/com/google/devtools/dash:__pkg__"],
    deps = [
        "@com_google_appengine_java//:api",
        "//external:javax/servlet/api",
        "//src/main/protobuf:proto_dash",
        "@bazel_tools//third_party:apache_velocity",
        "@bazel_tools//third_party:guava",
    ],
)
