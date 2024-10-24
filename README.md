# WHY FORK?

**A fork version of the linux kernel.**  
**Fork time: _2024/10/24 UTC+8_**

Given that _**Linus Torvalds**_ and _**Greg Kroah-Hartman**_ have removed lots of maintainers with `<.ru>` top-level domain emails and one maintainer with a Russian identity from the `MAINTAINERS` file,[^1] [^2] as well as publicly insulted and trampled on some builders of the open-source community.[^3] [^4] [^5]

To prevent such incidents in the future, I have decided to fork a copy of the Linux kernel source code for future needs.

## Linux kernel

There are several guides for kernel developers and users. These guides can
be rendered in a number of formats, like HTML and PDF. Please read
Documentation/admin-guide/README.rst first.

In order to build the documentation, use ``make htmldocs`` or
``make pdfdocs``.

There are various text files in the Documentation/ subdirectory,
several of them using the reStructuredText markup notation.

Please read the Documentation/process/changes.rst file, as it contains the
requirements for building and running the kernel, and information about
the problems which may result by upgrading your kernel.

[^1]: [MAINTAINERS: Remove some entries due to various compliance requirements. - Greg Kroah-Hartman](https://lore.kernel.org/all/2024101835-tiptop-blip-09ed@gregkh/)  
[^2]: [GitHub Commit: "MAINTAINERS: Remove some entries due to various compliance requirements. · torvalds/linux@6e90b67"](https://github.com/torvalds/linux/commit/6e90b675cf942e50c70e8394dfb5862975c3b3b2)  
[^3]: [Re: Revert "MAINTAINERS: Remove some entries due to various compliance requirements." - Linus Torvalds](https://lore.kernel.org/all/CAHk-=whNGNVnYHHSXUAsWds_MoZ-iEgRMQMxZZ0z-jY4uHT+Gg@mail.gmail.com/)  
[^4]: [安同开源社区有关 Linux 基金会及其职员不当行为的谴责 | 安同开源社区 (AOSC)](https://aosc.io/news/detail/2024-10-24-condemnation-of-the-linux-foundation-and-its-employees.zh-cn.md)  
[^5]: [English version of link 4](./WHY%20FORK/20241024-condemnation-english.md)
