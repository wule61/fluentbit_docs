# 依赖

[Fluent Bit](http://fluentbit.io) 使用非常低的 CPU 和内存消耗，它与大多数基于 x86，x86\_64，arm32v7 和 arm64v8 的平台兼容。为了进行构建，您需要在系统中使用以下组件来进行构建:

* 编译器: GCC or clang
* CMake
* Flex & Bison: 仅当您启用流处理器或记录访问器功能时\(两者都默认启用\)

在核心功能中没有其他依赖项，对于某些依赖于第三方组件的功能，例如带有特殊后端库\(如 kafka\)，这些包含在主代码仓库中。
