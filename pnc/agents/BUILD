package(default_visibility = ["//visibility:public"])

cc_library(
    name = "agents",
    srcs = ["agents.cc"],
    hdrs = ["agents.h"],
    deps = [
        "//pnc/agents/sample:sample_agent",
        "//pnc/agents/jcvb:jcvb_agent",
	"//pnc/agents/darkartist:darkartist",
        "//pnc/simulation:vehicle_agent_factory",
    ],
    alwayslink = 1,
)
