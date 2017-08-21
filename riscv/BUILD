cc_library(
    name = "riscv",
    srcs = glob(["*.cc"], exclude=["insn_template.cc"]),    
    hdrs = glob(["*.h", "insns/*.h"]),
    deps = ["//debug_rom:debug_rom", "//softfloat:softfloat", "@riscv_fesvr//fesvr:fesvr"],
)


