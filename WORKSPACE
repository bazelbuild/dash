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

# WORKSPACE file example to download Java AppEngine dependencies.
load('@bazel_tools//tools/build_rules/appengine:appengine.bzl', 'appengine_repositories')
appengine_repositories()

maven_jar(
    name = "easymock",
    artifact = "org.easymock:easymock:3.1",
)