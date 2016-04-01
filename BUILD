load("@io_bazel_rules_appengine//appengine:appengine.bzl", "appengine_war")

appengine_war(
    name = "dash",
    data = ["//src/main/webapp"],
    data_path = "/src/main/webapp",
    jars = ["//src/main/java:java-bin_deploy.jar"],
)
