licenses(["reciprocal"])

package(default_visibility = ["//visibility:public"])

load(
    "@io_bazel_rules_scala//scala:scala.bzl",
    "scala_binary",
    "scala_library",
    "scala_test",
    "scala_macro_library",
    "scala_specs2_junit_test",
)
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "specs2_matcher_extra_2_11",
    jars = [
        "@org_specs2_specs2_matcher_extra_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:specs2_analysis_2_11",
        "//third_party/org/specs2:specs2_matcher_2_11",
    ],
)

scala_import(
    name = "specs2_scalacheck_2_11",
    jars = [
        "@org_specs2_specs2_scalacheck_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scalacheck:scalacheck_2_11",
        "//third_party/org/specs2:specs2_core_2_11",
    ],
)

scala_import(
    name = "specs2_core_2_11",
    jars = [
        "@org_specs2_specs2_core_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang:scala_reflect",
        "//third_party/org/specs2:specs2_matcher_2_11",
    ],
)

scala_import(
    name = "specs2_junit_2_11",
    jars = [
        "@org_specs2_specs2_junit_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/junit",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:specs2_core_2_11",
    ],
)

scala_import(
    name = "specs2_gwt_2_11",
    jars = [
        "@org_specs2_specs2_gwt_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/chuusai:shapeless_2_11",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:specs2_core_2_11",
        "//third_party/org/specs2:specs2_matcher_extra_2_11",
        "//third_party/org/specs2:specs2_scalacheck_2_11",
    ],
)

scala_import(
    name = "specs2_markdown_2_11",
    jars = [
        "@org_specs2_specs2_markdown_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/chuusai:shapeless_2_11",
        "//third_party/org/pegdown",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:specs2_common_2_11",
        "//third_party/org/specs2:specs2_core_2_11",
    ],
)

scala_import(
    name = "specs2_codata_2_11",
    jars = [
        "@org_specs2_specs2_codata_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scalaz:scalaz_concurrent_2_11",
        "//third_party/org/scalaz:scalaz_core_2_11",
        "//third_party/org/scalaz:scalaz_effect_2_11",
    ],
)

scala_import(
    name = "specs2_form_2_11",
    jars = [
        "@org_specs2_specs2_form_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:specs2_core_2_11",
        "//third_party/org/specs2:specs2_markdown_2_11",
        "//third_party/org/specs2:specs2_matcher_extra_2_11",
    ],
)

scala_import(
    name = "specs2_matcher_2_11",
    jars = [
        "@org_specs2_specs2_matcher_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:specs2_common_2_11",
    ],
)

scala_import(
    name = "specs2_2_11",
    jars = [
    ],
    exports = [
        "//third_party/org/specs2:specs2_analysis_2_11",
        "//third_party/org/specs2:specs2_core_2_11",
        "//third_party/org/specs2:specs2_form_2_11",
        "//third_party/org/specs2:specs2_gwt_2_11",
        "//third_party/org/specs2:specs2_html_2_11",
        "//third_party/org/specs2:specs2_junit_2_11",
        "//third_party/org/specs2:specs2_markdown_2_11",
        "//third_party/org/specs2:specs2_matcher_extra_2_11",
        "//third_party/org/specs2:specs2_mock_2_11",
        "//third_party/org/specs2:specs2_scalacheck_2_11",
    ],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "classycle",
    jars = [
        "@org_specs2_classycle//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "specs2_common_2_11",
    jars = [
        "@org_specs2_specs2_common_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang:scala_reflect",
        "//third_party/org/scala-lang/modules:scala_parser_combinators_2_11",
        "//third_party/org/scala-lang/modules:scala_xml_2_11",
        "//third_party/org/scalaz:scalaz_concurrent_2_11",
        "//third_party/org/scalaz:scalaz_core_2_11",
        "//third_party/org/scalaz:scalaz_effect_2_11",
        "//third_party/org/specs2:specs2_codata_2_11",
    ],
)

scala_import(
    name = "specs2_analysis_2_11",
    jars = [
        "@org_specs2_specs2_analysis_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_compiler",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:classycle",
        "//third_party/org/specs2:specs2_core_2_11",
        "//third_party/org/specs2:specs2_matcher_2_11",
    ],
)

scala_import(
    name = "specs2_html_2_11",
    jars = [
        "@org_specs2_specs2_html_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/ccil/cowan/tagsoup",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:specs2_form_2_11",
    ],
)

scala_import(
    name = "specs2_mock_2_11",
    jars = [
        "@org_specs2_specs2_mock_2_11//jar:file",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/hamcrest:hamcrest_core",
        "//third_party/org/mockito:mockito_core",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:specs2_core_2_11",
    ],
)
