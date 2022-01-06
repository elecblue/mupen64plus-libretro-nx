# Mupen64Plus-Next (elecblue Fork)

Mupen64Plus-Next is a N64 emulation library for the [libretro API](http://www.libretro.com/), based on (and the successor to) the old Mupen64Plus core (see below).

#### What is different about this fork?

I don't have much experience with this sort of programming, so it's foremost a way for me to learn libretro core development by fixing issues I encounter while trying to use the official core. What started off as an attempt to fix one issue -- immediate crashes when loading a ROM -- is becoming a hobby project to make improvements to the core focused on macOS (and iOS, I suppose).

The biggest change I hope to make is to introduce Metal compatibility for the core's implimentation of GLideN64. If I ever actually succeed in doing this it will probably take a while, so without help from more advanced macOS API devs, I don't recommend putting all of your eggs in my basket. 

> **Sidenote:**  
On account of my amateur knowledge of emulator development, I'll take as much help as I can get and all PRs will be considered -- bonus points if you also teach me the specifics of what your changes are doing. 

#### Used Technologies

The following projects have been incorporated into this repository:

- [Mupen64Plus](https://github.com/mupen64plus/mupen64plus-core)
- [GLideN64](https://github.com/gonetz/GLideN64)
- [cxd4](https://github.com/cxd4/rsp)
- [parallel-rsp](https://github.com/Themaister/parallel-rsp)
- [angrylion-rdp-plus](https://github.com/ata4/angrylion-rdp-plus) (Currently based on it's [ParaLLel](https://github.com/libretro/parallel-n64/) variant)

#### Acknowledgments

A special thanks to:

- m4xw and contributors to the original Mupen64Plus-libretro-nx project.
- The Mupen64Plus Team, especially Gillou68310.
- gonetz and those that have worked on GLideN64, especially fzurita.
- The Authors of cxd4 and angrylion-rdp-plus (ata4).
- themaister for parallel-rsp and parallel-rdp (including the Vulkan integration).
- Everyone in the libretro Team.
