find_package(rosidl_default_generators REQUIRED)

rosidl_generate_interfaces(${PROJECT_NAME}
    "msg/Bumper.msg"
    "msg/ChargingState.msg"
    "msg/DefineTune.msg"
    "msg/Mode.msg"
    "PlayTune.msg"
)