load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library", "scala_binary", "scala_test")

scala_binary(
  name = 'app',
  srcs = glob(['*.scala']),
  main_class = 'core.App',
  scalacopts = ['-deprecation', '-feature', '-unchecked'],
)
