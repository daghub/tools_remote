package(default_visibility = ["//visibility:public"])

proto_library(
    name = "remote_execution_log_proto",
    srcs = ["remote_execution_log.proto"],
    deps = [
        "@com_google_protobuf//:timestamp_proto",
        "@googleapis//:google_bytestream_bytestream_proto",
        "@googleapis//:google_devtools_remoteexecution_v1test_remote_execution_proto",
        "@googleapis//:google_longrunning_operations_proto",
        "@googleapis//:google_rpc_status_proto",
        "@googleapis//:google_watch_v1_proto",
        "@remoteapis//build/bazel/remote/execution/v2:remote_execution_proto",
    ],
)

java_proto_library(
    name = "remote_execution_log_java_proto",
    deps = [":remote_execution_log_proto"],
)

proto_library(
    name = "nvidiametadata_proto",
    srcs = [":nvidiametadata.proto"],
)

java_proto_library(
    name = "nvidia_java_proto",
    deps = [":nvidiametadata_proto"],
)

proto_library(
    name = "buildbarn_resourceusage_proto",
    srcs = [":resourceusage.proto"],
    deps = [
        "@com_google_protobuf//:any_proto",
        "@com_google_protobuf//:duration_proto",
        "@com_google_protobuf//:empty_proto",
        "@com_google_protobuf//:timestamp_proto",
    ],
)

java_proto_library(
    name = "buildbarn_resourceusage_java_proto",
    deps = [":buildbarn_resourceusage_proto"],
)
