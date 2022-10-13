workspace(name = "arm-toolchain_test")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

new_http_archive(
  name = "arm_gcc_linux_toolchain",
  build_file = "compilers/gcc-arm-linux-gnueabihf.BUILD",
  urls = ["https://releases.linaro.org/components/toolchain/binaries/7.5-2019.12/arm-linux-gnueabihf/gcc-linaro-7.5.0-2019.12-x86_64_arm-linux-gnueabihf.tar.xz"],
  strip_prefix = "gcc-linaro-7.5.0-2019.12-x86_64_arm-linux-gnueabihf"
)
new_http_archive(
  name = "aarch64_gcc_linux_toolchain",
  build_file = "compilers/gcc-aarch64-linux-gnu.BUILD",
  urls = ["https://releases.linaro.org/components/toolchain/binaries/7.5-2019.12/aarch64-linux-gnu/gcc-linaro-7.5.0-2019.12-x86_64_aarch64-linux-gnu.tar.xz"],
  strip_prefix = "gcc-linaro-7.5.0-2019.12-x86_64_aarch64-linux-gnu"
)

new_local_repository(
  name = "device_sysroot",
  path = "/opt/device_sysroot",
  build_file = "toolchain/device_sysroot.BUILD",
)
