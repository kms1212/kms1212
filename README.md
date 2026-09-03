# README

I work on **computer architecture and systems**, with interests spanning ISA design, processor implementation, compilers, ABIs, operating systems, runtimes, and low-level system software.

A recurring question in my work is how responsibilities and information should be distributed across system layers. I am particularly interested in the interfaces that connect those layers: what each layer should expose, what it should hide, and which responsibilities belong on either side of a boundary.

I tend to approach systems as a whole rather than treating an architectural layer in isolation. An ISA decision may affect compiler lowering, ABI conventions, operating-system state management, and hardware complexity at the same time. I like following those consequences across the stack and looking for principles that remain useful across several seemingly different design problems.

Most of my research and engineering is implementation-driven. I build experimental systems to examine whether an idea remains coherent once it has to work with the surrounding layers, and use the resulting implementation constraints to revise the original design.

## Research & Engineering Interests

* Computer architecture and ISA design
* Processor and RTL design
* Hardware/software co-design
* Compiler and architecture interfaces
* ABI and system interface design
* Operating-system architecture
* Runtime and resource abstraction
* Firmware and low-level system software
* Experimental computing systems

## What I'm Working On

### Bedrock

An experimental ISA and processor architecture, currently developed across architectural specification, ABI and compiler support, emulation, RTL implementation, and operating-system interfaces.

### foliOS / Strata

An experimental operating-system and runtime project exploring kernel architecture, isolation, resource and namespace models, and interfaces between system components.

### EHBC

A long-running homebrew computing project involving custom hardware, firmware, boot environments, operating-system bring-up, and hardware/software integration.

## Technical Experience

**Architecture / ISA**

<div align="center">

![m68k](https://img.shields.io/badge/m68k-E1140A?style=flat-square\&logo=Motorola\&logoColor=white)
![x86/IA32](https://img.shields.io/badge/x86%2FIA32-0071C5?style=flat-square\&logo=Intel\&logoColor=white)
![x86/AMD64](https://img.shields.io/badge/x86%2FAMD64-ED1C24?style=flat-square\&logo=AMD\&logoColor=white)
![AVR](https://img.shields.io/badge/AVR-2961B8?style=flat-square\&logoColor=white)
![ARM](https://img.shields.io/badge/ARM-0091BD?style=flat-square\&logo=Arm\&logoColor=white)
![MOS 6502](https://img.shields.io/badge/MOS%206502-000000?style=flat-square\&logoColor=white)

</div>

**Programming Languages**

<div align="center">

![Ada](https://img.shields.io/badge/Ada-000000?style=flat-square)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square\&logo=C\&logoColor=white)
![C#](https://img.shields.io/badge/C%23-064F8C?style=flat-square\&logo=C%20Sharp\&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square\&logo=C%2B%2B\&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square\&logo=Dart\&logoColor=white)
![Fortran](https://img.shields.io/badge/Fortran-734F96?style=flat-square\&logo=Fortran\&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=JavaScript\&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square\&logo=PHP\&logoColor=white)
![Perl](https://img.shields.io/badge/Perl-39457E?style=flat-square\&logo=Perl\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=Python\&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-black?style=flat-square\&logo=Rust\&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square\&logo=Swift\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=TypeScript\&logoColor=white)

</div>

**Hardware Description Languages**

<div align="center">

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-000000?style=flat-square)
![Verilog](https://img.shields.io/badge/Verilog-000000?style=flat-square)
![VHDL](https://img.shields.io/badge/VHDL-000000?style=flat-square)

</div>

**Frameworks / Platforms**

<div align="center">

![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square\&logo=.NET\&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square\&logo=Django\&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square\&logo=Electron\&logoColor=white)
![Express.js](https://img.shields.io/badge/Express-000000?style=flat-square\&logo=Express\&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-1C2024?style=flat-square\&logo=Expo)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square\&logo=Flutter)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square\&logo=Spring%20Boot\&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square\&logo=Vue.js\&logoColor=white)

</div>

**Toolchains / Build / EDA**

<div align="center">

![LLVM](https://img.shields.io/badge/LLVM-262D3A?style=flat-square\&logo=LLVM\&logoColor=white)
![GCC](https://img.shields.io/badge/GCC-5C6EB8?style=flat-square\&logo=GNU\&logoColor=white)
![GNU Binutils](https://img.shields.io/badge/GNU%20Binutils-A42E2B?style=flat-square\&logo=GNU\&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square\&logo=CMake\&logoColor=white)
![LibreLane](https://img.shields.io/badge/LibreLane-000000?style=flat-square)
![Meson](https://img.shields.io/badge/Meson-402780?style=flat-square)
![Verilator](https://img.shields.io/badge/Verilator-000000?style=flat-square)
![Yosys](https://img.shields.io/badge/Yosys-000000?style=flat-square)
![GNU Bison](https://img.shields.io/badge/GNU%20Bison-A42E2B?style=flat-square\&logo=GNU\&logoColor=white)
![GNU Flex](https://img.shields.io/badge/GNU%20Flex-A42E2B?style=flat-square\&logo=GNU\&logoColor=white)

</div>

**Tools / Platforms**

<div align="center">

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=Docker\&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square\&logo=Figma\&logoColor=white)

</div>

**DBMS**

<div align="center">

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square\&logo=MySQL\&logoColor=white)
![Oracle SQL](https://img.shields.io/badge/Oracle%20SQL-CC6699?style=flat-square\&logo=Oracle\&logoColor=white)

</div>

## Histories

* 부산광역시교육청 미래교육원 정보영재과정 수료
* 부산대학교 과학영재교육원 IT-수학융합 심화·사사과정 수료
* 2020 대학부설 과학영재교육원 사사과정 연구성과 발표대회 한국과학기술원 총장상
* 2022 AI 기반 프로젝트 경진대회 1위 (부산광역시 교육감상)

## Links

<a href="https://github.com/kms1212" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a> <a href="https://kms1212.github.io" target="_blank"><img src="https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=GitHub%20Pages&logoColor=white"/></a> <a href="https://velog.io/@kms1212" target="_blank"><img src="https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=Velog&logoColor=black"/></a>
