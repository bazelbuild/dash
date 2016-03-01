load("@bazel_tools//tools/build_rules/appengine:appengine.bzl", "appengine_war")

appengine_war(
    name = "dash",
    data = ["//src/main/webapp"],
    data_path = "/src/main/webapp",
    jars = ["//src/main/java:java-bin_deploy.jar"],
)
