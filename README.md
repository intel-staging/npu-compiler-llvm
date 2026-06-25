# OpenVINO™ Intel® NPU Compiler – LLVM Fork Notice

[![npu/release/20.x](https://img.shields.io/badge/Archive_release_branch-npu/release/20.x-lightgray)](https://github.com/intel-staging/npu-compiler-llvm/tree/npu/release/20.x)
[![pr/npu/release/20.x](https://img.shields.io/badge/Open_a_PR_to-npu/release/20.x-lightgray)](https://github.com/intel-staging/npu-compiler-llvm/compare/npu/release/20.x..?)

[![npu/release/21.x](https://img.shields.io/badge/Active_release_branch-npu/release/21.x-blue)](https://github.com/intel-staging/npu-compiler-llvm/tree/npu/release/21.x)
[![pr/npu/release/21.x](https://img.shields.io/badge/Open_a_PR_to-npu/release/21.x-blue)](https://github.com/intel-staging/npu-compiler-llvm/compare/npu/release/21.x..?)

[![npu/main](https://img.shields.io/badge/Active_experimental_branch-npu/main-yellow)](https://github.com/intel-staging/npu-compiler-llvm/tree/npu/main)
[![pr/npu/main](https://img.shields.io/badge/Open_a_PR_to-npu/main-yellow)](https://github.com/intel-staging/npu-compiler-llvm/compare/npu/main..?)

This repository is a fork of [llvm/llvm-project](https://github.com/llvm/llvm-project).
It is designed to provide the core functionality of LLVM and MLIR projects, along with a set of NPU Compiler-specific patches. These modifications serve as the baseline for the [OpenVINO™ Intel® NPU Compiler](https://github.com/openvinotoolkit/npu_compiler).

## Branching strategy

The default branch of this repository is [npu/main](https://github.com/intel-staging/npu-compiler-llvm/tree/npu/main) that is forked from the `main` branch of [llvm/llvm-project](https://github.com/llvm/llvm-project) with some patches applied.
The NPU Compiler releases are based on official LLVM releases with NPU-specific patches. To contribute to the NPU-specific version of LLVM, please open a Pull Request to one of the following branches:

* [npu/release/20.x](https://github.com/intel-staging/npu-compiler-llvm/tree/npu/release/20.x) - Archived.
* [npu/release/21.x](https://github.com/intel-staging/npu-compiler-llvm/tree/npu/release/21.x) - Contribute to the current active baseline for the NPU Compiler LLVM dependency.
* [npu/main](https://github.com/intel-staging/npu-compiler-llvm/tree/npu/main) - Contribute to the current experimental baseline for the NPU Compiler LLVM dependency.

## Security Policy

Intel® Corporation is committed to addressing security vulnerabilities quickly and transparently. To report a potential security issue in this project, please refer to our
[Security Policy](./SECURITY.md).

---

# The LLVM Compiler Infrastructure

[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/llvm/llvm-project/badge)](https://securityscorecards.dev/viewer/?uri=github.com/llvm/llvm-project)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/8273/badge)](https://www.bestpractices.dev/projects/8273)
[![libc++](https://github.com/llvm/llvm-project/actions/workflows/libcxx-build-and-test.yaml/badge.svg?branch=main&event=schedule)](https://github.com/llvm/llvm-project/actions/workflows/libcxx-build-and-test.yaml?query=event%3Aschedule)

Welcome to the LLVM project!

This repository contains the source code for LLVM, a toolkit for the
construction of highly optimized compilers, optimizers, and run-time
environments.

The LLVM project has multiple components. The core of the project is
itself called "LLVM". This contains all of the tools, libraries, and header
files needed to process intermediate representations and convert them into
object files. Tools include an assembler, disassembler, bitcode analyzer, and
bitcode optimizer.

C-like languages use the [Clang](https://clang.llvm.org/) frontend. This
component compiles C, C++, Objective-C, and Objective-C++ code into LLVM bitcode
-- and from there into object files, using LLVM.

Other components include:
the [libc++ C++ standard library](https://libcxx.llvm.org),
the [LLD linker](https://lld.llvm.org), and more.

## Getting the Source Code and Building LLVM

Consult the
[Getting Started with LLVM](https://llvm.org/docs/GettingStarted.html#getting-the-source-code-and-building-llvm)
page for information on building and running LLVM.

For information on how to contribute to the LLVM project, please take a look at
the [Contributing to LLVM](https://llvm.org/docs/Contributing.html) guide.

## Getting in touch

Join the [LLVM Discourse forums](https://discourse.llvm.org/), [Discord
chat](https://discord.gg/xS7Z362),
[LLVM Office Hours](https://llvm.org/docs/GettingInvolved.html#office-hours) or
[Regular sync-ups](https://llvm.org/docs/GettingInvolved.html#online-sync-ups).

The LLVM project has adopted a [code of conduct](https://llvm.org/docs/CodeOfConduct.html) for
participants to all modes of communication within the project.
