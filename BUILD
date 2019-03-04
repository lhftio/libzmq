package(default_visibility = ["//visibility:public"])

cc_library(
    name = "zmq",
    includes = [
        "src",
    ],
    strip_include_prefix =
        "include",
    hdrs = glob([
        "include/*.h",
    ]),
    srcs = glob([
        "include/*.h",
        "src/**/*.h",
        "src/**/*.hpp",
        "src/**/*.cpp",
    ]),
    defines = [
        "ZMQ_BUILD_DRAFT_API",
    ],
    deps = [
               "@pgm//:pgm",
            ],

)
