java_library(
    name = "util",
    srcs = ["ProtoInputStream.java"],
    deps = [
        "//external:javax/servlet/api",
        "//third_party:protobuf",
    ],
)

java_test(
    name = "dash",
    srcs = [
        "DashRequestTest.java",
    ],
    deps = [
        "@appengine-java//:jars",
        "@easymock//jar",
        ":util",
        "//src/main/java:servlets",
        "//src/main/protobuf:proto_dash",
        "//third_party:junit4",
        "//third_party:truth",
    ],
)
