# 说明

## 环境介绍
基于 CentOS Linux release 7.4.1708 (Core) 上的 glibc (2.17)

```bash
$ uname -a
Linux bogon 3.10.0-693.el7.x86_64 #1 SMP Tue Aug 22 21:09:27 UTC 2017 x86_64 x86_64 x86_64 GNU/Linux

$ cat /etc/centos-release-upstream
Derived from Red Hat Enterprise Linux 7.4 (Source)

$ cat /etc/centos-release
CentOS Linux release 7.4.1708 (Core)
```

```bash
$ /lib64/libc.so.6
GNU C Library (GNU libc) stable release version 2.17, by Roland McGrath et al.
Copyright (C) 2012 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.
There is NO warranty; not even for MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.
Compiled by GNU CC version 4.8.5 20150623 (Red Hat 4.8.5-16).
Compiled on a Linux 3.10.0 system on 2017-08-01.
Available extensions:
        The C stubs add-on version 2.1.2.
        crypt add-on version 2.1 by Michael Glad and others
        GNU Libidn by Simon Josefsson
        Native POSIX Threads Library by Ulrich Drepper et al
        BIND-8.2.3-T5B
        RT using linux kernel aio
libc ABIs: UNIQUE IFUNC
For bug reporting instructions, please see:
<http://www.gnu.org/software/libc/bugs.html>.
```

## 源码
[glibc source](https://www.gnu.org/software/libc/sources.html)
```bash
$ git clone git://sourceware.org/git/glibc.git

$ git checkout glibc-2.17
```
