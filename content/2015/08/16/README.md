# Awesome List Updates on Aug 16, 2015

7 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Tips](/content/git-tips/tips/README.md)

## Show all commits in the current branch yet to be merged to master

```sh
git cherry -v master
```

**Alternatives:**

```sh
git cherry -v master <branch-to-be-merged>
```

## [2. Awesome Cpp](/content/fffaraz/awesome-cpp/README.md)

### CLI

*   [gflags](https://gflags.github.io/gflags/) - Commandline flags module for C++. \[BSD]

### Physics

*   [Box2D (⭐8k)](https://github.com/erincatto/Box2D) - A 2D physics engine for games. \[BSD-like]

## [3. Awesome Dotnet](/content/quozd/awesome-dotnet/README.md)

### SDK and API Clients

*   [Azure PowerShell (⭐4.2k)](https://github.com/Azure/azure-powershell) - A set of PowerShell cmdlets for developers and administrators to develop, deploy and manage Microsoft Azure applications

## [4. Awesome Linux Containers](/content/Friz-zy/awesome-linux-containers/README.md)

### Foundations

*   [OPEN CONTAINER INITIATIVE](https://www.opencontainers.org/)\
    The Open Container Initiative is a lightweight, open governance structure, to be formed under the auspices of the Linux Foundation, for the express purpose of creating open industry standards around container formats and runtime.
*   [Cloud Native Computing Foundation](https://cncf.io/)\
    The Cloud Native Computing Foundation will create and drive the adoption of a new set of common container technologies informed by technical merit and end user value, and inspired by Internet-scale computing.

### Specifications

*   [Open Container Specifications (⭐2.9k)](https://github.com/opencontainers/specs)\
    This project is where the Open Container Initiative Specifications are written. This is a work in progress.
*   [App Container basics (⭐8.8k)](https://github.com/coreos/rkt/blob/master/Documentation/app-container.md)\
    App Container (appc) is an open specification that defines several aspects of how to run applications in containers: an image format, runtime environment, and discovery protocol.

### Clouds

*   [Google Cloud Platform](https://cloud.google.com/container-engine/)\
    Run Docker containers on Google Cloud Platform, powered by Kubernetes. Google Container Engine actively schedules your containers, based on declared needs, on a managed cluster of virtual machines.

### Hypervisors

*   [LXD (⭐4k)](https://github.com/lxc/lxd)\
    Daemon based on liblxc offering a REST API to manage LXC containers.
*   [OpenVZ](https://openvz.org/)\
    OpenVZ is container-based virtualization for Linux. OpenVZ creates multiple secure, isolated Linux containers (otherwise known as VEs or VPSs) on a single physical server enabling better server utilization and ensuring that applications do not conflict.

### Containers

*   [runc (⭐11k)](https://github.com/opencontainers/runc)\
    runc is a CLI tool for spawning and running containers according to the OCS specification.
*   [Rocket (⭐8.8k)](https://github.com/coreos/rkt)\
    rkt (pronounced "rock-it") is a CLI for running app containers on Linux. rkt is designed to be composable, secure, and fast. Based on AppC specification.
*   [LXC (⭐4.1k)](https://github.com/lxc/lxc)\
    LXC is the well known set of tools, templates, library and language bindings. It's pretty low level, very flexible and covers just about every containment feature supported by the upstream kernel.
*   [Vagga (⭐1.8k)](https://github.com/tailhook/vagga)\
    Vagga is a fully-userspace container engine inspired by Vagrant and Docker, specialized for development environments.
*   [libct (⭐101)](https://github.com/xemul/libct)\
    Libct is a containers management library which provides convenient API for frontend programs to rule a container during its whole lifetime.
*   [libvirt](https://libvirt.org/drvlxc.html)\
    A big toolkit to interact with the virtualization capabilities of recent versions of Linux (and other OSes).

### Sandboxes

*   [Firejail](https://l3net.wordpress.com/projects/firejail/)\
    Firejail is a SUID sandbox program that reduces the risk of security breaches by restricting the running environment of untrusted applications using Linux namespaces, seccomp-bpf and Linux capabilities.
*   [Subuser (⭐881)](https://github.com/subuser-security/subuser)\
    Securing the Linux desktop with Docker.
*   [Snappy](https://wiki.ubuntu.com/SecurityTeam/Specifications/SnappyConfinement)\
    Snappy Ubuntu Core is a new rendition of Ubuntu with transactional updates - a minimal server image with the same libraries as today’s Ubuntu, but applications are provided through a simpler mechanism.
*   [xdg-app](https://wiki.gnome.org/Projects/SandboxedApps)\
    xdg-app is a system for building, distributing and running sandboxed desktop applications on Linux.

### Partial Access

*   [nsenter](http://man7.org/linux/man-pages/man1/nsenter.1.html)\
    Run program with namespaces of other processes. Part of the util-linux.
*   [ip-netns](http://man7.org/linux/man-pages/man8/ip-netns.8.html)\
    Process network namespace management. Part of the iproute2.
*   [unshare](http://man7.org/linux/man-pages/man1/unshare.1.html)\
    Run program with some namespaces unshared from parent. Part of the util-linux.
*   [python-nsenter (⭐136)](https://github.com/zalando/python-nsenter)\
    This Python package allows entering Linux kernel namespaces (mount, IPC, net, PID, user and UTS) by doing the "setns" syscall.
*   [butter](https://pypi.python.org/pypi/butter)\
    Python library to interface to low level linux features (inotify, fanotify, timerfd, signalfd, eventfd, containers) with asyncio support.
*   [pyspaces (⭐87)](https://github.com/Friz-zy/pyspaces)\
    Works with Linux namespaces through glibc with pure python.

### Security / Links

*   [Are Docker containers really secure?](https://opensource.com/business/14/7/docker-security-selinux)
*   [Bringing new security features to Docker](https://opensource.com/business/14/9/security-for-docker)
*   [Docker, Linux Containers (LXC), and security](http://www.slideshare.net/jpetazzo/docker-linux-containers-lxc-and-security)
*   [For containers, security is problem #1](http://www.itworld.com/article/2920349/security/for-containers-security-is-problem-1.html)
*   [Linux Container Security](https://mjg59.dreamwidth.org/33170.html)
*   [Ask HN: Best Linux sandbox?](https://news.ycombinator.com/item?id=10030868)

### Security / Levels of security problems

*   regular application
*   always untrusted -> know it
*   suid bit -> mount with nosuid
*   limit available syscall -> seccomp-bpf, grsec
*   system services like cron, ssh
*   run as root -> isolate via bastion host or vm
*   using /dev -> "devices" control group\
    The following device nodes are created in the container by default.\
    The Docker images are also mounted with nodev, which means that even if a device node was pre-created in the image, it could not be used by processes within the container to talk to the kernel.\
    /dev/console,/dev/null,/dev/zero,/dev/full,/dev/tty\*,/dev/urandom,/dev/random,/dev/fuse
*   root calls -> capabilities (cap\_sys\_admin warning!)\
    Here is the current list of capabilities that Docker uses: chown, dac\_override, fowner, kill, setgid, setuid, setpcap, net\_bind\_service, net\_raw, sys\_chroot, mknod, setfcap, and audit\_write.\
    Docker removes several of these capabilities including the following:\
    CAP\_SETPCAP 	Modify process capabilities\
    CAP\_SYS\_MODULE 	Insert/Remove kernel modules\
    CAP\_SYS\_RAWIO 	Modify Kernel Memory\
    CAP\_SYS\_PACCT 	Configure process accounting\
    CAP\_SYS\_NICE 	Modify Priority of processes\
    CAP\_SYS\_RESOURCE 	Override Resource Limits\
    CAP\_SYS\_TIME 	Modify the system clock\
    CAP\_SYS\_TTY\_CONFIG 	Configure tty devices\
    CAP\_AUDIT\_WRITE 	Write the audit log\
    CAP\_AUDIT\_CONTROL 	Configure Audit Subsystem\
    CAP\_MAC\_OVERRIDE 	Ignore Kernel MAC Policy\
    CAP\_MAC\_ADMIN 	Configure MAC Configuration\
    CAP\_SYSLOG 	Modify Kernel printk behavior\
    CAP\_NET\_ADMIN 	Configure the network\
    CAP\_SYS\_ADMIN 	Catch all\
    uses /proc, /sys -> remount ro, drop cap\_sys\_admin; security modules like selinux or apparmor; some part of this fs are "namespace-aware"\
    Docker mounts these file systems into the container as "read-only" mount points.\
    . /sys\
    . /proc/sys\
    . /proc/sysrq-trigger\
    . /proc/irq\
    . /proc/bus\
    Copy-on-write file systems\
    Docker uses copy-on-write file systems. This means containers can use the same file system image as the base for the container. When a container writes content to the image, it gets written to a container specific file system. This prevents one container from seeing the changes of another container even if they wrote to the same file system image. Just as important, one container can not change the image content to effect the processes in another container.
*   uid 0 -> user namespaces, uid 0 mappet to random uid outside
*   system services like devices, network, filesystems
*   kernel drivers, network stack, security policies
*   general like immutable infrastructure
*   container is ro
*   write to small separate rw nosuid part

### Security / Technologies for security

*   SELinux
*   Cgroups
*   file systems under /sys
*   /proc/sys, /proc/sysrq-trigger, /proc/irq, /proc/bus
*   /dev/mem
*   /dev/sd\* file system devices
*   kernel modules

## [5. Awesome Erlang](/content/drobakowski/awesome-erlang/README.md)

### Miscellaneous

*   [erld (⭐194)](https://github.com/ShoreTel-Inc/erld) - erld is a small program designed to solve the problem of running Erlang programs as a UNIX daemon.

## [6. Awesome Typescript](/content/dzharii/awesome-typescript/README.md)

### Offline / Other (Plugins || Cross-platform || OSS || Free)

*   :octocat: [Typescript addin for (⭐29)](https://github.com/mrward/typescript-addin) MonoDevelop, SharpDevelop and Xamarin Studio;  a short [review article](http://lastexitcode.com/blog/2015/04/01/TypeScriptSupportInXamarinStudio/)

### :dollar: Paid Courses / Chrome Extensions

*   [Angular with TypeScript](http://www.pluralsight.com/courses/angular-typescript) (Pluralsight)

## [7. Engineering Blogs](/content/kilimchoi/engineering-blogs/README.md)

### Companies / L companies

*   LinkedIn <https://engineering.linkedin.com/blog>

---

- Prev: [Aug 17, 2015](/content/2015/08/17/README.md)
- Next: [Aug 15, 2015](/content/2015/08/15/README.md)