package(default_visibility = ['//tools/aarch64_compiler:__pkg__',
                              '//cubemx/mo_proto:__pkg__'])

filegroup(
  name = 'gcc',
  srcs = [
    '@aarch64_gcc_linux_toolchain//:gcc',
    'aarch64-linux-gnu-gcc',
  ],
)

filegroup(
  name = 'ar',
  srcs = [
    '@aarch64_gcc_linux_toolchain//:ar',
    'aarch64-linux-gnu-ar',
  ],
)

filegroup(
  name = 'ld',
  srcs = [
    '@aarch64_gcc_linux_toolchain//:ld',
    'aarch64-linux-gnu-ld',
  ],
)

filegroup(
  name = 'nm',
  srcs = [
    '@aarch64_gcc_linux_toolchain//:nm',
    'aarch64-linux-gnu-nm',
  ],
)

filegroup(
  name = 'objcopy',
  srcs = [
    '@aarch64_gcc_linux_toolchain//:objcopy',
    'aarch64-linux-gnu-objcopy',
  ],
)

filegroup(
  name = 'objdump',
  srcs = [
    '@aarch64_gcc_linux_toolchain//:objdump',
    'aarch64-linux-gnu-objdump',
  ],
)

filegroup(
  name = 'strip',
  srcs = [
    '@aarch64_gcc_linux_toolchain//:strip',
    'aarch64-linux-gnu-strip',
  ],
)

filegroup(
  name = 'as',
  srcs = [
    '@aarch64_gcc_linux_toolchain//:as',
    'aarch64-linux-gnu-as',
  ],
)

filegroup(
  name = 'tool-wrappers',
  srcs = [
    ':gcc',
    ':ar',
    ':ld',
    ':nm',
    ':objcopy',
    ':objdump',
    ':strip',
    ':as',
  ],
)
