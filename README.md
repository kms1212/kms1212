# Minsu Kwon (권민수)

**Systems researcher — from ISA to OS · Full-stack web & app developer**

I work on **computer architecture and systems**: ISA design, processor implementation, compilers, ABIs, operating systems, and low-level system software. I am most interested in the interfaces between those layers — what each one should expose, what it should hide, and how a decision at one level ripples through the rest of the stack.

My work is implementation-driven. I build experimental systems end to end to see whether an idea stays coherent once it has to work with its surrounding layers, and feed those constraints back into the design. Outside research, I build web services and applications professionally.

## What I'm Working On

### [Bedrock](https://github.com/bedrock-proj)

A 64-bit ISA and systems-software specification: variable-length encoding, restartable repeated execution, an optional scalable-vector extension, an LP64 C ABI, an executable Sail model, an LLVM toolchain, and an emulator.

[spec](https://github.com/bedrock-proj/spec) · [reference](https://bedrock-proj.github.io/spec/) · [llvm-project](https://github.com/bedrock-proj/llvm-project) · [doomgeneric](https://github.com/bedrock-proj/doomgeneric) (DOOM port)

### [foliOS / Strata](https://github.com/foliOS-project)

An experimental operating system built around **Strata**, a kernel exploring the *Ambikernel* model — process isolation as the baseline, with signed modules allowed into kernel-adjacent domains when the lower transition cost justifies it. Comes with its own ABI, toolchain, and interface definition language.

[foliOS](https://github.com/foliOS-project/foliOS) · [foliSDK](https://github.com/foliOS-project/foliSDK) · [sidlc](https://github.com/foliOS-project/sidlc) · [sma](https://github.com/foliOS-project/sma)

### [EHBC](https://github.com/ehbc-project)

*Extensible Homebrew Computer* — a long-running homebrew computer project spanning custom hardware, firmware, boot environments, and operating-system bring-up.

[hardware-design](https://github.com/ehbc-project/hardware-design) · [ehbc-firmware](https://github.com/ehbc-project/ehbc-firmware) · [emos](https://github.com/ehbc-project/emos)

## Selected Projects

* [**ofsl2**](https://github.com/kms1212/ofsl2) — C library for manipulating file-system structures on drives and disk images, with a C++ wrapper
* [**WxWave**](https://github.com/kms1212/WxWave) — GTKWave alternative written in C++ and wxWidgets
* [**JSIS**](https://github.com/kms1212/JSIS) — intranet service server for students of Busan Jung-ang High School
* [**2022-busanedu-ai-project**](https://github.com/kms1212/2022-busanedu-ai-project) — AI-based project, 1st place at the 2022 Busan AI project competition
* [**pyApplicationFramework**](https://github.com/kms1212/pyApplicationFramework) — SwiftUI-style declarative GUI framework for Python

## Technical Experience

### Systems & Hardware

**Languages**

<div align="center">

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=C&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=C%2B%2B&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-black?style=flat-square&logo=Rust&logoColor=white)
![Ada](https://img.shields.io/badge/Ada-000000?style=flat-square)
![Fortran](https://img.shields.io/badge/Fortran-734F96?style=flat-square&logo=Fortran&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white)

</div>

**Architecture / ISA**

<div align="center">

![m68k](https://img.shields.io/badge/m68k-E1140A?style=flat-square&logo=Motorola&logoColor=white)
![x86/IA32](https://img.shields.io/badge/x86%2FIA32-0071C5?style=flat-square&logo=Intel&logoColor=white)
![x86/AMD64](https://img.shields.io/badge/x86%2FAMD64-ED1C24?style=flat-square&logo=AMD&logoColor=white)
![AVR](https://img.shields.io/badge/AVR-2961B8?style=flat-square&logoColor=white)
![ARM](https://img.shields.io/badge/ARM-0091BD?style=flat-square&logo=Arm&logoColor=white)
![MOS 6502](https://img.shields.io/badge/MOS%206502-000000?style=flat-square&logoColor=white)

</div>

**Hardware Description Languages**

<div align="center">

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-000000?style=flat-square)
![Verilog](https://img.shields.io/badge/Verilog-000000?style=flat-square)
![VHDL](https://img.shields.io/badge/VHDL-000000?style=flat-square)

</div>

**Toolchains / Build / EDA**

<div align="center">

![LLVM](https://img.shields.io/badge/LLVM-262D3A?style=flat-square&logo=LLVM&logoColor=white)
![GCC](https://img.shields.io/badge/GCC-5C6EB8?style=flat-square&logo=GNU&logoColor=white)
![GNU Binutils](https://img.shields.io/badge/GNU%20Binutils-A42E2B?style=flat-square&logo=GNU&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=CMake&logoColor=white)
![LibreLane](https://img.shields.io/badge/LibreLane-000000?style=flat-square)
![Meson](https://img.shields.io/badge/Meson-402780?style=flat-square)
![Verilator](https://img.shields.io/badge/Verilator-000000?style=flat-square)
![Yosys](https://img.shields.io/badge/Yosys-000000?style=flat-square)
![GNU Bison](https://img.shields.io/badge/GNU%20Bison-A42E2B?style=flat-square&logo=GNU&logoColor=white)
![GNU Flex](https://img.shields.io/badge/GNU%20Flex-A42E2B?style=flat-square&logo=GNU&logoColor=white)

</div>

### Web & Application

**Languages**

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-064F8C?style=flat-square&logo=C%20Sharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=Dart&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=Swift&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=PHP&logoColor=white)
![Perl](https://img.shields.io/badge/Perl-39457E?style=flat-square&logo=Perl&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=C%2B%2B&logoColor=white)

</div>

**Frameworks / Platforms**

<div align="center">

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=Vue.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express-000000?style=flat-square&logo=Express&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=Django&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=Spring%20Boot&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=.NET&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=Flutter)
![Expo](https://img.shields.io/badge/Expo-1C2024?style=flat-square&logo=Expo)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=Electron&logoColor=white)

</div>

**Databases / Tools**

<div align="center">

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white)
![Oracle SQL](https://img.shields.io/badge/Oracle%20SQL-CC6699?style=flat-square&logo=Oracle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white)

</div>

## Awards & Programs

* 2022 AI 기반 프로젝트 경진대회 1위 (부산광역시 교육감상) — [repo](https://github.com/kms1212/2022-busanedu-ai-project)
* 2020 대학부설 과학영재교육원 사사과정 연구성과 발표대회 한국과학기술원 총장상
* 부산대학교 과학영재교육원 IT-수학융합 심화·사사과정 수료
* 부산광역시교육청 미래교육원 정보영재과정 수료

## Links

<a href="https://kms1212.github.io" target="_blank"><img src="https://img.shields.io/badge/Website-kms1212.github.io-1a1a18?style=flat-square"/></a> <a href="https://github.com/kms1212" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>
