# Copyright 2015 The Bazel Authors. All rights reserved.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#    http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
workspace(name = "io_bazel_dash")

# WORKSPACE file example to download Java AppEngine dependencies.

git_repository(
    name = "io_bazel_rules_appengine",
    remote = "https://github.com/bazelbuild/rules_appengine.git",
    tag = "0.0.3",
)

git_repository(
    name = "io_bazel",
    remote = "https://github.com/bazelbuild/bazel.git",
    tag = "0.2.3",
)

load("@io_bazel_rules_appengine//appengine:appengine.bzl", "appengine_repositories")
appengine_repositories()

maven_jar(
    name = "easymock",
    artifact = "org.easymock:easymock:3.1",
)
