package(default_visibility = ["//visibility:public"])

cc_library(
    name = "zmq",
    includes = [
        "src",
    ],
    hdrs = glob([
        "include/*.h",
    ]),
    srcs = glob([
        "src/**/*.h",
        "src/**/*.hpp",
        "src/**/*.cpp",
    ]),
    copts = [
        "-DZMQ_BUILD_DRAFT_API",
    ],
)
