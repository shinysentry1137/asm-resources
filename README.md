# Assembly Language Learning Resources

The most common thing I teach assembly (ASM) for is reverse engineering, but I also put a lot of my effort into covering low-level computer architecture fundamentals that you all will probably need at some point if you want to understand how small systems actually work. Reverse engineering becomes a lot easier when you understand what the processor is doing beneath higher-level languages.

Note: Some of these don't focus on ASM as their main topic. That's okay, you're still going to need it as part of the skillset to understand what you're doing in the challenges. 

## Wikis, References, and Long-Form Learning

### [OSDev Wiki](https://wiki.osdev.org/)

One of the best free references for low-level systems programming. Covers operating system development, x86 architecture, bootloaders, memory management, interrupts, filesystems, BIOS/UEFI, device drivers, and many other topics that help explain how software interacts directly with hardware.

### [Wikibooks: Assembly Languages](https://en.wikibooks.org/wiki/Category:Shelf:Assembly_languages)

A collection of freely available books covering multiple assembly languages, architectures, and programming techniques. Useful as a reference when learning different instruction sets or comparing syntax between assemblers.

### [The Art of Assembly Language by Randall Hyde](https://www.randallhyde.com/AssemblyLanguage/www.artofasm.com/index.html)

A classic book for learning x86 assembly language from the ground up. It explains the language itself, but also gives a lot of guidance on how to explore processor architecture, data representation, optimization, and systems programming concepts.

Three complete editions are available online (DOS 16-bit, Windows 32-bit, and Linux 32-bit). A modern published edition is also available from [No Starch Press](https://nostarch.com/art-arm-assembly-volume-1).

### [Intel 64 and IA-32 Architectures Software Developer's Manual](https://www.intel.com/content/www/us/en/developer/articles/technical/intel-sdm.html)

This is the official technical reference published by Intel for their x86 processors. This family of manuals define how their instructions work, but also processor behavior, registers, memory management, paging, exceptions, virtualization, debugging features, and much more that's probably relevant if you're into computer science and looking beyond what's useful for only cybersecurity. Intel recommends that you use the stuff here as authoritative specification for working with their processors.

### [Compiler Explorer (Godbolt)](https://godbolt.org/)

An interactive tool that lets you write code in C, C++, Rust, Zig, and other difficult languages while instantly viewing the generated assembly output.

It's excellent if you need something to demonstrate the following skills that advanced cybersecurity learners are expected to know about:

* How different compilers generate assembly
* The effects of optimization levels
* Calling conventions
* Instruction selection
* Differences between CPU targets

One of my favorite tools for connecting high-level source code with the machine instructions that actually execute instead of being a black box.

### [xv6 by MIT CSAIL PDOS](https://pdos.csail.mit.edu/6.828/xv6)

A small educational operating system based on early Unix. MIT developed this project specifically for teaching operating system internals. The codebase is intentionally simple enough to understand while still showing off real concepts such as processes, virtual memory, system calls, interrupts, scheduling, and filesystems. (There's more but those are the ones you want if you're doing this as part of a degree program or job training for advanced cybersecurity that involves reverse engineering.) Source code for xv6 is available on [GitHub](https://github.com/mit-pdos/xv6-public).

### [Zero Day Arcade](https://zerodayarcade.com/)

A collection of interactive tutorials and exercises covering reverse engineering, exploitation, binary analysis, programming, and related low-level computing topics through progressively more challenging hands-on activities.

### [PortSwigger Web Security Academy](https://portswigger.net/web-security)

Free interactive lessons covering modern web security concepts with browser-based labs. While not assembly-focused, many reverse engineering students eventually analyze network traffic, web applications, authentication systems, and client-side code. Free account required to save lab progress.

---

# Hands-On Reverse Engineering

### [Malware Unicorn](https://malwareunicorn.org/)

Interactive reverse engineering workshops featuring malware analysis exercises, assembly tutorials, and browser-friendly walkthroughs. Excellent introduction to practical reverse engineering techniques. No account required.

### [crackmes.one](https://crackmes.one/)

Large community-built collection of reverse engineering challenges covering many architectures, operating systems, and difficulty levels. Account optional.

### [CrackMyApp](https://crackmy.app/)

Community-submitted reverse engineering challenges focused primarily on desktop applications. Account optional.

### [Crackme Collection by Phracker](https://phrackery.github.io/crackmes/)

Curated collection of classic crackmes gathered up from multiple sources. Small collection. No account required.

### [Reverse Engineering Range](https://rerange.org/)

Interactive reverse engineering platform that features guided challenges, scoreboards, and multiple styles of exercises. Curated content. Account optional.

### [OWASP MAS Crackmes](https://mas.owasp.org/crackmes/)

Reverse engineering challenges for Android and iOS applications provided by the OWASP Mobile Application Security project. Great if you're learning mobile binary analysis and application security. Less great if you're interested in fundamentals (don't go into this without any familiarity of app security). No account required.

### [Reverse Engineering Challenges by Dennis Yurichev](https://challenges.re/)

A collection of reverse engineering exercises created by Dennis Yurichev, author of [Reverse Engineering for Beginners (RE4B)](https://beginners.re/). Also explains some mathematical concepts relevant to low-level operations. No account required.

### [pwn.college](https://pwn.college/)

Large collection of guided security challenges covering reverse engineering, binary exploitation, assembly, operating systems, cryptography, and many other low-level topics that can help you if you're currently studying or working with ASM in some capacity. Account optional.

### [pwnable.kr](https://pwnable.kr/)

Fairly gamified capture-the-flag style binary exploitation and reverse engineering challenges maintained by Kyung Hee University. Small but highly regarded collection. Account optional.

### [Microcorruption (Embedded Security CTF)](https://microcorruption.com/)

Embedded systems reverse engineering game developed by NCC Group. Players get to analyze firmware, understand microcontroller assembly, and exploit embedded devices through progressively harder challenges. Account optional.

### [CyLab Security Academy](https://learn.cylabacademy.org/get-started)

Educational security challenge platform maintained by Carnegie Mellon University's CyLab. Formerly known as PicoCTF. Includes increasingly difficult guided exercises, labs, and capture-the-flag challenges which are good for beginners who are looking to make the switch over to intermediate learning.

---

More coming soon!
