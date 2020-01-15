| Guest OS | Guest Arch | Windows | Mac | Linux | binfmt |
| --- | --- | --- | --- | --- | :--- |
| Microsoft DOS | i386 | [emu2](https://github.com/dmsc/emu2) (Cygwin)[Console-Only] |  | [emu2](https://github.com/dmsc/emu2) [Console-Only] | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft OS/2 | i386 | | | [2ine](https://github.com/darkstar/2ine) (Linux)[Console-Only] | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows 3.x | i386 | [Wine](https://wiki.winehq.org/) (Cross-platform) | [Wine](https://wiki.winehq.org/) (Cross-platform) | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows NT | arm64 | | [Wine](https://wiki.winehq.org/) (Cross-platform) | | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows NT | armhf | | [Wine](https://wiki.winehq.org/) (Cross-platform) | | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows NT | axp | | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows NT | i386 | [Wine](https://wiki.winehq.org/) (Cross-platform) | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows NT | ia64 | | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows NT | mips | | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows NT | ppc | | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows NT | x64 | [Wine](https://wiki.winehq.org/) (Cross-platform) | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows CE | arm | | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows CE | i386 | | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows CE | mipsii | | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |
| Microsoft Windows CE | sh4 | | ```:MZexec:M::MZ::/usr/bin/exerunsuit.sh:``` |

| Guest OS | Guest Arch | Windows | Mac | Linux | binfmt |
| --- | --- | --- | --- | --- | :--- |
| Linux | arm64 | [qemu-aarch64-static](https://github.com/qemu/qemu) (Linux) | ```:aarch64:M::\x7fELF\x02\x01\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\xb7:\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff:/usr/bin/qemu-aarch64-static:```|
| Linux | armhf | [qemu-arm-static](https://github.com/qemu/qemu) (Linux) | ```:arm:M::\x7fELF\x01\x01\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x28\x00:\xff\xff\xff\xff\xff\xff\xff\x00\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff\xff:/usr/bin/qemu-arm-static:```|
| Linux | armel | [qemu-armeb-static](https://github.com/qemu/qemu) (Linux) | ```:arm:M::\x7fELF\x01\x01\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x28\x00:\xff\xff\xff\xff\xff\xff\xff\x00\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff\xff:/usr/bin/qemu-arm-static:```|
| Linux | axp | [qemu-alpha-static](https://github.com/qemu/qemu) (Linux) | ```:alpha:M::\x7fELF\x02\x01\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x26\x90:\xff\xff\xff\xff\xff\xfe\xfe\xff\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff\xff:/usr/bin/qemu-alpha-static:```|
| Linux | hppa | [qemu-hppa-static](https://github.com/qemu/qemu) (Linux) | ```:hppa:M::\x7f\x45\x4c\x46\x01\x02\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x0f:\xff\xff\xff\xff\xff\xff\xff\x00\xff\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff:/usr/bin/qemu-hppa-static:```|
| Linux | i386 | [qemu-i386-static](https://github.com/qemu/qemu) (Linux), [Box86](https://github.com/ptitSeb/box86) (Linux for 32-bit little endian CPUs) | ```:i386:M::\x7fELF\x01\x01\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x03\x00:\xff\xff\xff\xff\xff\xfe\xfe\xff\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff\xff:/usr/local/bin/qemu-i386-static:```|
| Linux | ia64 |  | |
| Linux | m68k | [qemu-m68k-static](https://github.com/qemu/qemu) (Linux) | ```:m68k:M::\x7fELF\x01\x02\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x04:\xff\xff\xff\xff\xff\xff\xfe\xfe\xff\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff:/usr/bin/qemu-m68k-static:```|
| Linux | mips | [qemu-mips-static](https://github.com/qemu/qemu) (Linux) | ```:mips:M::\x7fELF\x01\x02\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x08:\xff\xff\xff\xff\xff\xff\xff\x00\xff\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff:/usr/bin/qemu-mips-static:```|
| Linux | mips64 | [qemu-mips64-static](https://github.com/qemu/qemu) (Linux) | ```:mips64:M::\x7fELF\x02\x02\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x08:\xff\xff\xff\xff\xff\xff\xff\x00\xff\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff:/usr/bin/qemu-mips64-static:```|
| Linux | mipsel | [qemu-mipsel-static](https://github.com/qemu/qemu) (Linux) | ```:mipsel:M::\x7fELF\x01\x01\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x08\x00:\xff\xff\xff\xff\xff\xff\xff\x00\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff\xff:/usr/bin/qemu-mipsel-static:```|
| Linux | ppc | [qemu-ppc-static](https://github.com/qemu/qemu) (Linux) | ```:ppc:M::\x7fELF\x01\x02\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x14:\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff:/usr/bin/qemu-ppc-static:```|
| Linux | ppc64 | [qemu-ppc64-static](https://github.com/qemu/qemu) (Linux) | ```:ppc64:M::\x7fELF\x02\x02\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x15:\xff\xff\xff\xff\xff\xff\xff\x00\xff\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff:/usr/bin/qemu-ppc64-static:```|
| Linux | s390 | [qemu-s390x-static](https://github.com/qemu/qemu) (Linux) | ```:s390x:M::\x7fELF\x02\x02\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x16:\xff\xff\xff\xff\xff\xff\xff\x00\xff\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff:/usr/bin/qemu-s390x-static:```|
| Linux | sh4 | [qemu-sh4-static](https://github.com/qemu/qemu) (Linux) | ```:sh4:M::\x7fELF\x01\x01\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x2a\x00:\xff\xff\xff\xff\xff\xff\xff\x00\xff\xff\xff\xff\xff\xff\xff\xff\xfb\xff\xff\xff:/usr/bin/qemu-sh4-static:```|
| Linux | sparc | [qemu-sparc-static](https://github.com/qemu/qemu) (Linux) | ```:sparc:M::\x7fELF\x01\x02\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x02:\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff:/usr/bin/qemu-sparc-static:```|
| Linux | x64 | [qemu-x86_64-static](https://github.com/qemu/qemu) (Linux), [noah](https://github.com/linux-noah/noah) (Mac) | ```:x86_64:M::\x7fELF\x02\x01\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x3e\x00:\xff\xff\xff\xff\xff\xfe\xfe\x00\xff\xff\xff\xff\xff\xff\xff\xff\xfe\xff\xff\xff:/usr/local/bin/qemu-x86_64-static:```|

| Guest OS | Guest Arch | Windows | Mac | Linux | binfmt |
| --- | --- | --- | --- | --- | :--- |
| AmigaOS | m68k | [amitools](https://github.com/cnvogelg/amitools) (Cross-platform)[Console-Only] | ```:amiga68k:M::\x00\x00\x03\xf3\x00\x00\x00\x00:\xff\xff\xff\xff\xff\xff\xff\xff:/usr/local/bin/vamos:``` |
| AmigaOS | ppc | | |
| CP/M | i386 | | |
| BeOS | | | |
| NextStep | | | |
| RISC OS | | | |

| Guest OS | Guest Arch | Windows | Mac | Linux | binfmt |
| --- | --- | --- | --- | --- | :--- |
| System | m68k | | |
| Mac OS 9 | ppc | | |
| Apple Darwin | i386 | [Darling](https://www.darlinghq.org/) (Linux) | |
| Mac OS X | x64 | [Darling](https://www.darlinghq.org/) (Linux) | |

| Guest OS | Guest Arch | Windows | Mac | Linux | binfmt |
| --- | --- | --- | --- | --- | :--- |
| Amiga Unix | | | |
| Apollo DomainOS | | | |
| Apple AUX | | | |
| AROS | | | |
| Bell Labs Plan 9 | | | |
| Coherent Unix | | | |
| DEC ULTRIX | | | |
| DEC VAX/VMS | | | |
| Dell UNIX SVR | | | |
| DG UX UNIX | | | |
| HP-UX | | | |
| IBM AIX | | | |
| Intergraph CLIX | | | |
| Interix | | | |
| LynxOS | | | |
| MachTen | | | |
| Microsoft Xenix | | | |
| MINIX | | | |
| NetWare | | | |
| OSR5 Unix | | | |
| QNX | | | |
| RISC iX | | | |
| SGI IRIX | mips | [qemu-irix, qemu-irixn32](https://github.com/camthesaxman/qemu-irix) (Linux) | |
| SGI IRIX | mips64 | [qemu-irix64](https://github.com/camthesaxman/qemu-irix) (Linux) | |
| SINIX-Z | | | |
| Sony NEWS-OS 3.x | | | |
| Sun Solaris | sparc | [qemu-solaris](https://github.com/camthesaxman/qemu-irix) (Linux) | |
| Tru64 UNIX | | | |
| Ultrix | | | |
| UNICOS | | | |
| Unix V1 | PDP-11 | [Apout](https://github.com/DoctorWkt/Apout) (Unix) | ```:pdp11:M::\x07\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x01\x00\x09\xf0:\xff\xff\x00\x00\x00\x00\x00\x00\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff:/usr/local/bin/apout:``` |
| Unix V2 | PDP-11 | [Apout](https://github.com/DoctorWkt/Apout) (Unix) | ```:pdp11:M::\x07\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x01\x00\x09\xf0:\xff\xff\x00\x00\x00\x00\x00\x00\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff:/usr/local/bin/apout:``` |
| Unix V5 | PDP-11 | [Apout](https://github.com/DoctorWkt/Apout) (Unix) | ```:pdp11:M::\x07\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x01\x00\x09\xf0:\xff\xff\x00\x00\x00\x00\x00\x00\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff:/usr/local/bin/apout:``` |
| Unix V6 | PDP-11 | [Apout](https://github.com/DoctorWkt/Apout) (Unix) | ```:pdp11:M::\x07\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x01\x00\x09\xf0:\xff\xff\x00\x00\x00\x00\x00\x00\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff:/usr/local/bin/apout:``` |
| Unix V7 | PDP-11 | [Apout](https://github.com/DoctorWkt/Apout) (Unix) | ```:pdp11:M::\x07\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x01\x00\x09\xf0:\xff\xff\x00\x00\x00\x00\x00\x00\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff:/usr/local/bin/apout:``` |
| UnixWare | | | |
| Venix | | | |


| Guest OS | Guest Arch | Windows | Mac | Linux | binfmt |
| --- | --- | --- | --- | --- | :--- |
| 2.11BSD | PDP-11 | [Apout](https://github.com/DoctorWkt/Apout) (Unix) | ```:pdp11:M::\x07\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x01\x00\x09\xf0:\xff\xff\x00\x00\x00\x00\x00\x00\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff:/usr/local/bin/apout:``` |
| 2.9BSD | PDP-11 | [Apout](https://github.com/DoctorWkt/Apout) (Unix) | ```:pdp11:M::\x07\x01\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x01\x00\x09\xf0:\xff\xff\x00\x00\x00\x00\x00\x00\xff\xff\xff\xff\xff\xff\xff\xff\xff\xff:/usr/local/bin/apout:``` |
| 386BSD | | | |
| FreeBSD | | | |
| NetBSD | | | |
| OpenBSD | | | |
