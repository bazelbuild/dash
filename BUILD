load("/tools/build_rules/appengine/appengine", "appengine_war")

appengine_war(
    name = "dash",
    data = ["//src/main/webapp"],
    data_path = "/src/main/webapp",
    jars = ["//src/main/java:java-bin_deploy.jar"],
)
