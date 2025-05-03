# Awesome Qubes OS Overview

A curated list of awesome qubes os links

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/xn0px90/Awesome-Qubes-OS/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 xn0px90/Awesome-Qubes-OS](https://github.com/xn0px90/awesome-qubes-os) · ⭐ 109 · 🏷️ Miscellaneous

[ [Daily](/content/xn0px90/Awesome-Qubes-OS/README.md) / [Weekly](/content/xn0px90/Awesome-Qubes-OS/week/README.md) / Overview ]

---

# Awesome Qubes OS [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/xn0px90/Awesome-Qubes-OS/)[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![](https://img.shields.io/static/v1?label=Sponsor\&message=%E2%9D%A4\&logo=GitHub\&color=%23fe8e86)](https://github.com/sponsors/xn0px90)

## A curated list of Awesome Qubes OS links

A security-focused desktop operating system that aims to provide security through isolation.

This list is a collection of tools, projects, images, and resources conforming to the [Awesome Manifesto (⭐357k)](https://github.com/sindresorhus/awesome/blob/master/awesome.md).

Contributions *very welcome* but first see [Contributing](#contributing).

## Table of Contents

*   [Awesome Qubes OS ](#awesome-qubes-os-)
    *   [A curated list of Awesome Qubes OS links](#a-curated-list-of-awesome-qubes-os-links)
    *   [Table of Contents](#table-of-contents)
    *   [Qubes OS Websites](#qubes-os-websites)
    *   [System Information & Requirements](#system-information--requirements)
    *   [Downloading, Installing, Upgrading, and Building](#downloading-installing-upgrading-and-building)
    *   [How-to guides](#how-to-guides)
    *   [Templates](#templates)
    *   [VM-Hardening](#vm-hardening)
    *   [Customization](#customization)
    *   [GPU](#gpu)
    *   [ML LLM & AI](#ML-LLM--AI)
    *   [Clearnet & Anonymous Networking](#clearnet--anonymous-networking)
        *   [Wireguard](#wireguard)
        *   [OpenVPN](#openvpn)
        *   [Tor](#tor)
        *   [Anonymity](#anonymity)
        *   [Crypto](#crypto)
    *   [Kernels](#kernels)
        *   [Microkernels](#microkernels)
        *   [Unikernels](#unikernels)
        *   [Unikernel-like](#unikernel-like)
    *   [Qubes OS Server](#qubes-os-server)
    *   [Exploitation Tools](#exploitation-tools)
        *   [Xen Exploitation](#xen-exploitation)
        *   [Web articles](#web-articles)
    *   [Optics and Extra Info](#optics-and-extra-info)
    *   [Training and Materials](#training-and-materials)
    *   [Companies using Qubes OS](#companies-using-qubes-os)
    *   [Social media](#social-media)
    *   [Qubes OS Legends](#qubes-os-legends)
    *   [Contributing](#contributing)
    *   [Releases](#releases)
    *   [Adventure Further](#adventure-further)
    *   [License](#license)

## Qubes OS Websites

*   [Qubes OS](https://www.qubes-os.org) - Qubes OS is an operating system built out of securely-isolated compartments called Qubes.
*   [Qubes OS Development Documentation](https://dev.qubes-os.org/en/latest/) - Qubes OS development documentation.
*   [Qubes OS Developer Books](https://www.qubes-os.org/doc/devel-books/) - A list of various books that might be useful in learning some basics needed for Qubes development.
*   [Qubes OS Documentation](https://www.qubes-os.org/doc/) - Qubes OS main documentation.
*   [Qubes OS GitHub Documentation (⭐358)](https://github.com/QubesOS/qubes-doc) - Qubes OS GitHub latest documentation.
*   [Qubes OS News](https://www.qubes-os.org/news/) - Latest Qubes OS News.

## System Information & Requirements

*   [Architecture](https://www.qubes-os.org/doc/architecture/) - Qubes implements a security-by-compartmentalization approach.
*   [Audio virtualization](https://www.qubes-os.org/doc/audio-virtualization/) - VMs on Qubes OS have access to virtualized audio through the PulseAudio module.
*   [Certified Hardware](https://www.qubes-os.org/doc/certified-hardware/) - We aim for these vendors to be as diverse as possible in terms of geography, cost, and availability.
*   [Community-recommended hardware](https://www.qubes-os.org/doc/community-recommended-hardware/) - Community-recommended computers.
*   [Hardware compatibility list (HCL)](https://www.qubes-os.org/hcl/) - The HCL is a compilation of reports generated and submitted by users across various Qubes versions about their hardware’s compatibility with Qubes.
*   [System Requirements](https://www.qubes-os.org/doc/system-requirements/) - User documentation / Choyhe attacker doesn’t have access to all the software running in the other domains.
*   [Security-critical code](https://www.qubes-os.org/doc/security-critical-code/) - A list of security-critical (i.e., trusted) code components in Qubes OS.
*   [Storage pools](https://www.qubes-os.org/doc/storage-pools/) - Qubes OS implements a security-by-isolation (or security-by-compartmentalization) approach by providing the ability to easily create many security domains.
*   [Secondary storage](https://www.qubes-os.org/doc/secondary-storage/) - hese steps assume you have already created a separate volume group and thin pool (not thin volume) for your HDD.
*   [Networking](https://www.qubes-os.org/doc/networking/) - In Qubes, the standard Xen networking is used, based on backend driver in the driver domain and frontend drivers in VMs.
*   [Config files](https://www.qubes-os.org/doc/config-files/) - These files are placed in /rw, which survives a VM restart. That way, they can be used to customize a single VM instead of all VMs based on the same template. The scripts here all run as root.
*   [Disposable customization](https://www.qubes-os.org/doc/disposable-customization/) - A disposable can be based on any app qube.
*   [How to install software in dom0](https://www.qubes-os.org/doc/how-to-install-software-in-dom0/) - How to install a specific package
*   [How to make any file persistent (bind-dirs)](https://www.qubes-os.org/doc/bind-dirs/) - With bind-dirs any arbitrary files or folders can be made persistent in app qubes.
*   [How to mount a Qubes partition from another OS](https://www.qubes-os.org/doc/mount-from-other-os/) - When a Qubes OS install is unbootable or booting it is otherwise undesirable, this process allows for the recovery of files stored within the system.
*   [Installing contributed packages](https://www.qubes-os.org/doc/installing-contributed-packages/) - This page is for users who wish to install contributed packages.
*   [Managing qube kernels](https://www.qubes-os.org/doc/managing-vm-kernels/) - By default, VMs kernels are provided by dom0.
*   [Qubes service](https://www.qubes-os.org/doc/qubes-service/) - Usage documentation is in the qvm-service man page.
*   [RPC policies](https://www.qubes-os.org/doc/rpc-policy/) - This document explains the basics of RPC policies in Qubes.
*   [Resize disk image](https://www.qubes-os.org/doc/resize-disk-image/) - By default Qubes uses thin volumes for the disk images.
*   [Standalones and HVMs](https://www.qubes-os.org/doc/standalones-and-hvms/) - A standalone is a type of qube that is created by cloning a template. Unlike templates, however, standalones do not supply their root filesystems to other qubes.
*   [Volume backup and revert](https://www.qubes-os.org/doc/volume-backup-revert/) - With Qubes, it is possible to revert one of a VM’s storage volumes to a previous state using the automatic snapshot that is normally saved every time a VM is shutdown.

## Downloading, Installing, Upgrading, and Building

*   [Building (⭐21)](https://github.com/QubesOS/qubes-builderv2) - This is the second generation of the Qubes OS builder.
*   [Installing](https://www.qubes-os.org/doc/installation-guide/)  - Qubes OS installation guide!
*   [Qubes OS 4.2.3](https://www.qubes-os.org/downloads/) - Qubes OS 4.2.3 download.
*   [Qubes OS 4.2.3 Weekly Builds](https://qubes.notset.fr/iso/) - Qubes OS 4.2.3 Weekly Build download.
*   [Qubes OS 4.3 Weekly Alpha Builds](https://qubes.notset.fr/iso/) - Qubes OS 4.3 Weekly Alpha Build download.
*   [Upgrading](https://www.qubes-os.org/doc/upgrade/) - These guides are for upgrading from one version of Qubes to another.

## How-to guides

*   [How to resize dom0](https://forum.qubes-os.org/t/resize-dom0/10886) - Just in case anyone needs help with this to resize dom0 from 20G to 50G.
*   [How to back up, restore, and migrate](https://www.qubes-os.org/doc/how-to-back-up-restore-and-migrate/) - With Qubes, it’s easy and secure to back up and restore your whole system, as well as to migrate between two physical machines.
*   [How to copy and move files](https://www.qubes-os.org/doc/how-to-copy-and-move-files/) - This page is about copying and moving files.
*   [How to copy and paste text](https://www.qubes-os.org/doc/how-to-copy-and-paste-text/) - This page is about copying and pasting plain text.
*   [Inter-qube file copying (qfilecopy)](https://www.qubes-os.org/doc/qfilecopy/) - File copying with qfilecopy.
*   [How to copy from dom0](https://www.qubes-os.org/doc/how-to-copy-from-dom0/) - This page covers copying files and clipboard text between dom0 and domUs.
*   [How to enter fullscreen mode](https://www.qubes-os.org/doc/how-to-enter-fullscreen-mode/) - Normally, the Qubes GUI virtualization daemon restricts the VM from “owning” the full screen.
*   [How to install software](https://www.qubes-os.org/doc/how-to-install-software/) - When you wish to install software in Qubes OS, you should generally install it in a template.
*   [How to update](https://www.qubes-os.org/doc/how-to-update/) - This page is about updating your system while staying on the same supported version of Qubes OS.
*   [How to use PCI devices](https://www.qubes-os.org/doc/how-to-use-pci-devices/) - Unlike other devices (USB, block, mic), PCI devices need to be attached on VM-bootup.
*   [How to use USB devices](https://www.qubes-os.org/doc/how-to-use-usb-devices/) - Attaching USB devices to VMs requires a USB Qube.
*   [How to use block storage devices](https://www.qubes-os.org/doc/how-to-use-block-storage-devices/) - This page is part of device handling in Qubes.
*   [How to use devices](https://www.qubes-os.org/doc/how-to-use-devices/) - This is an overview of device handling in Qubes OS.
*   [How to use disposables](https://www.qubes-os.org/doc/how-to-use-disposables/) - A disposable is a lightweight Qube that can be created quickly and will self-destruct when closed.
*   [How to use optical discs](https://www.qubes-os.org/doc/how-to-use-optical-discs/) - Passthrough reading and recording (a.k.a., “burning”) are not supported by Qubes OS.
*   [How to persist Tailscale tunnel in QubesOS  (⭐2)](https://github.com/kennethrrosen/tailscale_QubesOS) - Tailscale is a mesh private network that lets you easily manage access to private resources or quickly SSH into devices on your network.
*   [How to use Qubes for journalists and Humans Rights Defenders (⭐19)](https://github.com/kennethrrosen/journoSEC) - A suite of tools for improving and streamlining the use of Qubes OS for reporters, edtiors, lawyers and aid workers. Work in progress.
    *   [PAM distress login for xscreensaver](https://github.com/kennethrrosen/qubes-PAM-distress-login/) - A simple setup for sending a distress email if forced to login to desktop beyond LUKS passwords.
    *   [Automated Arkenfox Qubes browser install (⭐19)](https://github.com/kennethrrosen/journoSEC/tree/main/mozilla/arkenfox) - Arkenfox config install for journalists
*   [How to Implement TPM Boot Verification](https://github.com/kennethrrosen/qubes-boot-verification) - Verify and validate boot process using PCR without Heads or AEM on systems using TPM 2.0
*   [How to open Urls in other qube](https://forum.qubes-os.org/t/opening-urls-files-in-other-qubes/19026) - This page is about opening URLs and files from one qube in a different qube.
*   [Qubes Salt Beginner’s Guide](https://forum.qubes-os.org/t/qubes-salt-beginners-guide/20126) - How to guide for beginners who enjoy an hands-on introduction with examples.
*   [Reverse Tethering & Screen Mirroring Qube for Android Device](https://forum.qubes-os.org/t/reverse-tethering-screen-mirroring-qube-for-android-device/28920) - Control your Android Device from Qubes OS while providing Network to the Android Device.
*   [How to migrate qubes to a new computer ](https://forum.qubes-os.org/t/how-to-efficiently-migrate-qubes-to-a-new-computer-with-a-direct-network-connection/23203/2) - How to efficiently migrate qubes to a new computer with a direct network connection
*   [USB MFP printer/scanner](https://forum.qubes-os.org/t/how-to-get-a-usb-mfp-printer-scanner-working-in-r4-2/24520) - How to get a USB MFP printer/scanner working in R4.2

## Templates

*   [archlinux-minimal template](https://forum.qubes-os.org/t/archlinux-minimal-template/19052) - This is a community guide, not an official guide.
*   [audio-qubes](https://forum.qubes-os.org/t/audio-qube/20685) - An audio qube acts as a secure handler for potentially malicious audio devices, preventing them from coming into contact with dom0
*   [Building a TemplateVM for a new OS](https://forum.qubes-os.org/docs?topic=18972) - If you don’t like using one of the existing templates because of specific administration, package management or other building needs, you can build a TemplateVM for your distribution of choice.
*   [Debian templates](https://www.qubes-os.org/doc/templates/debian/) - The Debian template is an officially supported template in Qubes OS.
*   [Auto Minimal Debian Template Creation](https://svensemmler.org/notes/deb-min-templates) - This page summarizes how to automate debian-minimal based template creation.
*   [Fedora templates](https://www.qubes-os.org/doc/templates/fedora/) - The Fedora template is the default template in Qubes OS.
*   [NetBSD templates](https://forum.qubes-os.org/t/netbsd-qube/19009) - Createa NetBSD template
*   [Linux HVMs](https://forum.qubes-os.org/docs?topic=19008) - Fixing Linux distro HVMs
*   [Manually Verifying Hashes of Installed Files](https://forum.qubes-os.org/t/manually-verifying-hashes-of-installed-files/23833) -  This guide explains how to manually verifying hashes of installed files.
*   [Minimal templates](https://www.qubes-os.org/doc/templates/minimal/) - The minimal templates are lightweight versions of their standard template counterparts.
*   [Multimedia template](https://forum.qubes-os.org/t/configuring-a-multimedia-templatevm/19055) - Configuring a “Multimedia” TemplateVM
*   [Pentesting: Parrot](https://qubes.3isec.org/Templates_4.2/) - Parrot Security is a Debian-based OS with over 600 tools for hacking, pentesting and software development. It is free, open source, secure, portable and customizable for various environments and devices
*   [Pentesting: BlackArch](https://forum.qubes-os.org/t/blackarch-templatevm/19010) - BlackArch Linux is an Arch Linux-based distribution for penetration testers and security researchers.
*   [Pentesting: Kali](https://forum.qubes-os.org/t/kali-template-available/1706) - How to create a Kali Linux VM.
*   [Pentesting: PTF](https://forum.qubes-os.org/t/penetration-testers-framework-ptf-templatevm/19011) - "The PenTesters Framework (PTF) is a Python script designed for Debian/Ubuntu/ArchLinux based distributions to create a similar and familiar distribution for Penetration Testing.
*   [Windows Qubes](https://www.qubes-os.org/doc/windows/) - Like any other unmodified OSes, Windows can be installed in Qubes as an HVM domain.
*   [Qvm-Create-Windows-Qube (⭐354)](https://github.com/ElliotKillick/qvm-create-windows-qube) - Qvm-Create-Windows-Qube is a tool for quickly and conveniently installing fresh new Windows qubes with Qubes Windows Tools (QWT) drivers automatically.
*   [Prestium OS](https://forum.qubes-os.org/t/prestium-os-setup/22545) - Prestium OS is a Tails OS-like live linux distro.
*   [Tails OS](https://forum.qubes-os.org/docs?topic=19012) - Tails stands for The Amnesic Incognito Live System. It is a live operating system that aims to preserve your privacy and anonymit.
*   [Templates](https://www.qubes-os.org/doc/templates/) - In Getting Started, we covered the distinction in Qubes OS between where you install your software and where you run your software.
*   [Template implementation](https://www.qubes-os.org/doc/template-implementation/) - Describes template implementation.
*   [Template manager](https://www.qubes-os.org/doc/template-manager/) -  A template manager application.
*   [Android VM options](https://forum.qubes-os.org/t/android-vm-options-and-blissos-installation-in-a-raw-vm-i-e-no-qubes-integration-collecting-all-realted-information/27582) -  There are multiple “android on PC” type distributions that one could try in a VM. Here are the 3!
*   [Waydroid template](https://forum.qubes-os.org/t/waydroid-template/23356) - This guide is for setting up minimal Waydroid template.
*   [Shadow qube (⭐7)](https://github.com/kennethrrosen/qubes-shadow-dvm) - The below script will create a Qube, launch the Tor browser, wait for the browser to close, then remove the qube and its RAM pool.
*   [Ubuntu 2022.4 minimal](https://qubes.3isec.org/Templates_4.2/) - Ubuntu 22.04 (Jammy Jellyfish) Releasesis an open-source software platform that runs everywhere from the PC to the server and the cloud.
*   [Ubuntu 2024.4 minimal](https://qubes.3isec.org/Templates_4.2/) - Ubuntu 24.04.1 (Noble Numbat) ReleasesUbuntu is an open-source software platform that runs everywhere from the PC to the server and the cloud.
*   [USB Qubes](https://www.qubes-os.org/doc/usb-qubes/) - A USB qube acts as a secure handler for potentially malicious USB devices, preventing them from coming into contact with dom0 (which could otherwise be fatal to the security of the whole system). I
*   [Xfce templates](https://www.qubes-os.org/doc/templates/xfce/) - If you would like to use Xfce (more lightweight compared to GNOME desktop environment) Linux distribution in your Qubes, you can install one of the available Xfce templates for Fedora, CentOS or Gentoo.
*   [GuixOS HVM](https://forum.qubes-os.org/t/install-guix-os-in-a-standalone-hvm/6209) - Install Guix OS in a standalone HVM
*   [Zoom Disp VM](https://forum.qubes-os.org/t/running-zoom-in-a-dispvm/19062) - Running Zoom in a DispVM.
*   [PrestiumOS HVM](https://forum.qubes-os.org/t/prestium-os-setup/22545/1) - Prestium OS is a Tails OS-like live linux distro.
*   [PiHole Cloudflared (⭐1)](https://github.com/92VV3M42d3v8/PiHole/blob/master/PiHole%20Cloudflared) - PiHole Cloudflared in QubesOS with NextDNS (DNS over Https).
*   [Fedora template in-place upgrade](https://www.qubes-os.org/doc/templates/fedora/in-place-upgrade/#detailed-instructions-for-standard-fedora-templates) - How to upgrade a Fedora template in-place.

## VM-Hardening

*   [Kicksecure](https://www.kicksecure.com/wiki/Kicksecure-Qubes_Security) - The following list of actionable items can help to improve security on the Qubes platform, and by extension Kicksecure ™ for Qubes users.
*   [Kicksecure for DISP-sys\*](https://forum.qubes-os.org/t/guide-kicksecure-for-disp-sys/13324) - How to create disposable sys-usb, sys-net, sys-firewall off a debian-11 minimal template with Kicksecure and other hardening features for DISP-sys\*.
*   [Qcrypt (⭐18)](https://github.com/3hhh/qcrypt) -qcrypt is a multilayer encryption tool for Qubes OS.
*   [Qubes-VM-hardening (⭐74)](https://github.com/tasket/Qubes-VM-hardening) - Leverage Qubes template non-persistence to fend off malware at VM startup: Lock-down, quarantine and check contents of /rw private storage that affect the execution environment.
*   [Anonymizing your MAC Address (⭐258)](https://github.com/Qubes-Community/Contents/blob/master/docs/privacy/anonymizing-your-mac-address.md) - Although the MAC address is not the only metadata broadcast by network hardware, changing your hardware's default MAC Address could be an important step in protecting privacy.
*   [Anti Evil Maid (AEM)](https://www.qubes-os.org/doc/anti-evil-maid/) - A user who frequently travels with a Qubes laptop holding sensitive data may be at a much higher risk of Evil Maid attacks than a home user with a stationary Qubes desktop.
*   [Data leaks](https://www.qubes-os.org/doc/data-leaks/) - Firewalling in Qubes is not intended to be a leak-prevention mechanism.
*   [Device handling security](https://www.qubes-os.org/doc/device-handling-security/) - Any additional ability a VM gains is additional attack surface.
*   [Dom0 secure updates](https://www.qubes-os.org/doc/dom0-secure-updates/) - Updating dom0
*   [Easily NAT qubes port to external network](https://dataswamp.org/~solene/2024-03-06-qubes-os-nat.html) - A script to ease the work of doing a NAT to expose a qube port to the physical network interface.
*   [Install Qubes OS with boot partition and a detached LUKS header on USB](https://forum.qubes-os.org/t/install-qubes-os-with-boot-partition-and-a-detached-luks-header-on-usb/26366) - The encrypted disk will look like an unused/empty unpartitioned disk.
*   [Firewall](https://www.qubes-os.org/doc/firewall/) - Every Qube in Qubes is connected to the network via a FirewallVM, which is used to enforce network-level policies.
*   [nft Firewall](https://forum.qubes-os.org/t/qubes-os-4-2-nftables-nft-firewall-guide/20933) - This is an example for a TCP redirection, for UDP you would have to replace tcp by udp.
*   [Passwordless root access in Qubes](https://www.qubes-os.org/doc/vm-sudo/) - In Qubes VMs there is no point in isolating the root account from the user account.
*   [Reducing the fingerprint of the text-based web browser w3m (⭐258)](https://github.com/Qubes-Community/Contents/blob/master/docs/configuration/w3m.md) - You can reduce the amount of information w3m gives about itself and the environment it is running in (and, by extension, you).
*   [Running Tails in Qubes (⭐258)](https://github.com/Qubes-Community/Contents/blob/master/docs/privacy/tails.md) - Tails stands for The Amnesic Incognito Live System.
*   [SaltStack (management software)](https://www.qubes-os.org/doc/salt/)
*   [Custom preferences for Brave browser in disposable qube](https://forum.qubes-os.org/t/set-custom-preferences-for-brave-browser-in-disposable-qube/27351) - The initial\_preferences json file can be used to configure the preferences that will be used by default in newly created profiles.
*   [Signal](https://forum.qubes-os.org/t/signal-messenger/19073) - It uses end-to-end encryption to secure all communications.
*   [Split GPG](https://www.qubes-os.org/doc/split-gpg/) - Split GPG implements a concept similar to having a smart card with your private GPG keys, except that the role of the “smart card” is played by another Qubes app Qube.
*   [Split SSH](https://deniszanin.com/using-split-ssh-gpg-in-qubes-os) - Split SSH implements a concept similar to having a smart card with your private SSH keys, except that the role of the “smart card” is played by another Qubes AppVM.
*   [Split dm-crypt (⭐23)](https://github.com/rustybird/qubes-split-dm-crypt) - Instead of directly attaching an encrypted LUKS1 partition from a source VM such as sys-usb to a destination VM and decrypting it there.
*   [U2F proxy](https://www.qubes-os.org/doc/u2f-proxy/) - The Qubes U2F Proxy is a secure proxy intended to make use of U2F two-factor authentication devices with web browsers without exposing the browser to the full USB stack, not unlike the USB keyboard and mouse proxies implemented in Qubes.
*   [Using Multi-Factor Authentication with Qubes (⭐258)](https://github.com/Qubes-Community/Contents/blob/master/docs/security/multifactor-authentication.md) - This page concerns multi-factor authentication for logging into external services, not for logging into Qubes itself.
*   [Using OnlyKey with Qubes OS](https://docs.crp.to/qubes.html) - The following setup instructions walk through the process of configuring dom0 and a USB qube so that OnlyKey will function as a keyboard and be able to communicate with the OnlyKey app (required for TOTP).
*   [Qrexec: secure communication across domains](https://www.qubes-os.org/doc/qrexec/) - The qrexec framework is used by core Qubes components to implement communication between domains.
*   [Qrexec: Qubes RPC internals](https://www.qubes-os.org/doc/qrexec-internals/) - The qrexec framework consists of a number of processes communicating with each other using a common IPC protocol, described in detail below.
*   [Qrexec: socket-based services](https://www.qubes-os.org/doc/qrexec-socket-services/) - The qrexec allows implementing services not only as executable files, but also as Unix sockets.
*   [Qubes memory manager (qmemman)](https://www.qubes-os.org/doc/qmemman/) - Provides automatic balancing of memory across participating PV and HVM domains, based on their memory demand
*   [TUFF](https://theupdateframework.io/security/) - We can think of a software update system as “secure” if:
*   [YubiKey](https://www.qubes-os.org/doc/yubikey/) - Most use cases for the YubiKey can be achieved exactly as described by the manufacturer or other instructions found online.
*   [Hardening sys-net](https://forum.qubes-os.org/t/hardening-sys-net/24345) - This guide works no matter whether or not you chose disposable sys-net or not. no nonsense guide, Lets get in!
*   [Nix in a Qubes OS AppVM](https://dataswamp.org/~solene/2023-05-15-qubes-os-install-nix.html) - How to install Nix in an AppVm.
*   [No file indexing](https://forum.qubes-os.org/t/disable-file-indexing-in-disposable-qubes/20747) - Disable file indexing in disposable qubes
*   [Qubes Shutdown Idle Script (⭐5)](https://github.com/QubesOS/qubes-app-shutdown-idle) - This is a simple script that watches the current qube for idleness and, if it's idle for more than 15 minutes (timeout time is defined in qubesidle.idleness\_monitor), shuts it down.
*   [qubes-ssh-agent (⭐3)](https://github.com/unman/qubes-ssh-agent) - This is an alternative approach to the existing qubes split-ssh.

## Customization

*   [AwesomeWM (window manager)](https://www.qubes-os.org/doc/awesomewm/) - This is an rpm package for awesomewm with the patches for Qubes.
*   [Brightness-Ajustment](https://forum.qubes-os.org/t/easy-brightness-adjustment/15902/2) - Easy brightness adjustment
*   [Bash completion](https://forum.qubes-os.org/docs?topic=13304) - How to install bash completion for Qubes OS commands.
*   [Custom icons](https://forum.qubes-os.org/t/where-is-the-most-optimal-place-to-put-custom-folder-icons/15740/3) - Place the custom folder icons \~/.local/share/icons is a persistent place to place the custom folder icons and so is /usr/share/icons.
*   [DPI scaling](https://forum.qubes-os.org/t/dpi-scaling/19064) - Qubes OS passes on dom0’s screen resolution to VMs (this can be seen in the output of xrandr) but doesn’t pass on dom0’s dpi value.
*   [i3 (window manager)](https://www.qubes-os.org/doc/i3/) - i3 is part of the stable repository (as of Qubes R3.1) and can be installed by using the dom0 update mechanism.
*   [KDE (desktop environment)](https://www.qubes-os.org/doc/kde/) -  KDE was the default desktop environment in Qubes
*   [Qubes-GUI-Rust (⭐9)](https://github.com/QubesOS/qubes-gui-rust) - Rust libraries for the Qubes OS GUI Protocol
*   [Suckless dwm (⭐12)](https://github.com/3o14r473/GUIDE_how-to-install-dwm-in-qubesos) - How to install dwm in Qubes OS.
*   [QubesOS Autostart Menu (⭐0)](https://github.com/kennethrrosen/Qubes-OS-Autostart-Menu/) - Speed up system boot process with a custom launch script
*   [Qubes-Scripts (⭐16)](https://github.com/Willy-JL/Qubes-Scripts) - Collection of custom scripts for Qubes OS.
*   [Playback performance](https://forum.qubes-os.org/t/improve-video-playback-performance-including-youtube/21946) - This guide will show you how to install the mpv player and use it with maximum performance.
*   [qubes-salt-video-playback](https://codeberg.org/brunoschroeder/qubes-salt-video-playback) - Qubes SaltStack configuration of Videos Playback VM
*   [sys-VPN notification setup](https://github.com/kennethrrosen/qubes_VPN_notifier) - Get VPN stats as a desktop notification
*   [Wayland agent (⭐19)](https://github.com/DemiMarie/qubes-wayland) - This is a GUI agent for Qubes OS that supports the \[Wayland] display server protocol. Compared to X11, Wayland is vastly simpler and aims to ensure every frame is perfect.
*   [Sys-gui Customization](https://forum.qubes-os.org/t/sys-gui-customization-minimal-fedora-and-alternate-desktop-environments-window-managers-de-wms/27093) - Minimal Fedora and Alternate Desktop Environments / Window Managers (DE/WMs)
*   [Tiling XFCE ](https://forum.qubes-os.org/t/tiling-xfce-windows-with-shortcut-keys/22840) - Titled windows in XFCE with shortcut keys.
*   [DPI scaling](https://forum.qubes-os.org/t/dpi-scaling/19064) - Qubes OS passes on dom0’s screen resolution to VMs (this can be seen in the output of xrandr) but doesn’t pass on dom0’s dpi value.
*   [Dark Theme](https://forum.qubes-os.org/t/dark-theme-in-dom0/18997) -  The following text describes how to change the default light theme to a dark theme.
*   [Rxvt Terminal](https://forum.qubes-os.org/t/rxvt-terminal/18992) - rxvt-unicode is an advanced and efficient vt102 emulator.
*   [CPU monitor per VMs](https://forum.qubes-os.org/t/cpu-monitor-per-vms/22829) - Individual VM monitoring.
*   [Custom App entries for the Q Menu](https://www.qubes-os.org/doc/app-menu-shortcut-troubleshooting/) - App menu shortcut troubleshooting.
*   [xfce dark mode ](https://forum.qubes-os.org/t/guide-xfce-global-dark-mode-in-qubes-4-0-4-1/10757) - Xfce global dark mode in Qubes
*   [Quick Quality-of-Life Improvements](https://forum.qubes-os.org/t/quick-quality-of-life-improvements/23380) - Custom scripts for everyday things.

## GPU

*   [GUI-configuration](https://www.qubes-os.org/doc/gui-configuration/) - Adjust your GUI configuration to meet your display needs.
*   [GUI-domain](https://www.qubes-os.org/doc/gui-domain/) - On this page, we describe how to set up a GUI domain.
*   [GUI-troubleshooting](https://www.qubes-os.org/doc/gui-troubleshooting/) - Learn to troubleshoot your GUI configuration.
*   [GUI-virtualization](https://www.qubes-os.org/doc/gui/) - All AppVM X applications connect to local (running in AppVM) Xorg servers.
*   [How-to-use-pci-devices](https://www.qubes-os.org/doc/how-to-use-pci-devices/) - This page is part of device handling in qubes.
*   [Install-nvidia-driver (⭐258)](https://github.com/Qubes-Community/Contents/blob/master/docs/configuration/install-nvidia-driver.md) - Nvidia proprietary driver installation.
*   [Nvidia-troubleshooting (⭐258)](https://github.com/Qubes-Community/Contents/blob/master/docs/troubleshooting/nvidia-troubleshooting.md) - Nvidia Troubleshooting Guide
*   [Gaming HVM](https://forum.qubes-os.org/t/create-a-gaming-hvm/19000)) - HVM for gaming!
*   [Salt: automating NVIDIA GPU passthrough](https://forum.qubes-os.org/t/wip-salt-automating-nvidia-gpu-passthrough/30038) - This “guide” aims to explore and give a practical example of leveraging SaltStack to achieve the same goal as NVIDIA GPU passthrough into Linux HVMs for CUDA applications.
*   [Qubes SaltStack configuration of Videos Playback VM](https://codeberg.org/brunoschroeder/qubes-salt-video-playback) - An mpv salt start step-by-step easy guide.
*   [Improve video playback performance including YouTube (ytfzf)](https://forum.qubes-os.org/t/improve-video-playback-performance-including-youtube-ytfzf/21946/1) - This guide will show you how to install the mpv player and use it with maximum performance.
*   [GPU passthrough with lots of RAM](https://forum.qubes-os.org/t/quick-howto-gpu-passthrough-with-lots-of-ram/21156) - GPU passthru with max RAM

## ML, LLM & AI

*   [Running local LLMs with or without GPU acceleration](https://forum.qubes-os.org/t/running-local-llms-with-or-without-gpu-acceleration/23283) - This guide explains how to install text-generation-webui (oobabooga) on Qubes OS.

## Troubleshooting

*   [Mounting a qube’s private storage in another qube](https://forum.qubes-os.org/t/mounting-a-qubes-private-storage-in-another-qube/19080) -  Useful for data recovery.
*   [Traffic Analysis in Qubes OS](https://zrubi.hu/en/2017/traffic-analysis-qubes/) - You can place a ProxyVM between your AppVMs and Your NetVM. This way we can create an ideal topology for traffic analysis.
*   [Analyze Qubes OS VM  (⭐1)](https://github.com/3hhh/qubes-performance) - Analyze Qubes OS VM startup performance.
*   [Url redirector (⭐35)](https://github.com/raffaeleflorio/qubes-url-redirector/) - This is a browser extension, aimed to improve surfing security.
*   [Changing your Time Zone](https://forum.qubes-os.org/t/changing-your-time-zone/18983) - Change the system’s time zone in terminal you can issue the timedatectl command with the option set-timezone.

## Clearnet & Anonymous Networking

### DNS

*   [dnscrypt-proxy](https://forum.qubes-os.org/t/guide-how-to-setup-a-sys-dns-qube/13749) -  Run dnscrypt-proxy inside of sys-net to encrypt and secure dns-requests.

### Wireguard

*   [Mullvad VPN (Fedora38 + WG)](https://mullvad.net/en/help/wireguard-on-qubes-os/) - Privacy-first VPN provider's guide for Qubes OS. This guide bears an optimal method for setting up a WG ProxyVM (i.e `sys-vpn`); you may substitute out Mullvad's WG configuration files in place of your own.
*   [Wireguard setup](https://forum.qubes-os.org/t/wireguard-vpn-setup/19141) - This guide assumes you are using a VPN service that has wireguard support.

### OpenVPN

*   [How To make a VPN Gateway in Qubes](https://forum.qubes-os.org/t/configuring-a-proxyvm-vpn-gateway/19061) - Qubes includes a number of tools that can make the client-side setup of your VPN more versatile and secure.
*   [Qubes-Tunnel (⭐25)](https://github.com/QubesOS-contrib/qubes-tunnel) - Manage, run, protect VPN connections in Proxy VMs.
*   [Mullvad VPN (Dedian 12 + OVPN)](https://mullvad.net/en/help/qubes-os-4-and-mullvad-vpn/) - Privacy-first VPN provider's guide for Qubes OS.
*   [Fedora 40 Minimal(OpenVPN)](https://forum.qubes-os.org/t/fedora-40-minimal-openvpn-qubes-4-2-six-easy-steps/27795) - Qubes 4.2 - Six Easy Steps!

### VLESS

*   [VLESS obfuscation VPN](https://forum.qubes-os.org/t/vless-obfuscation-vpn/20438) - The protocol mimics a long-running https session of Chrome and is hard to detect by DPI systems.

### Tor

*   [Snowflake Proxy in QubesOS](https://forum.qubes-os.org/t/functional-snowflake-proxy-in-sys-whonix-tor-control-panel-fix-full-guide/28866) - A Qubes-Whonix-17 Tor Control Panel snowflake proxy fix/installation guide.
*   [Qubes Tor onion services](https://www.qubes-os.org/news/2019/04/17/tor-onion-services-available-again/) -  Qubes OS Tor .onion links
*   [Onionizing Repositories](https://www.whonix.org/wiki/Onionizing_Repositories) - The guide explains how to configure experimental Tor onion services for APT repositories.
*   [Qubes OS Onion](http://www.qubesosfasa4zl44o4tws22di6kepyzfeqv3tg4e3ztknltfxqrymdad.onion) - Qubes OS onion address on the Tor network.
*   [QubesOS to be remotely manageable thru tor](https://www.whonix.org/wiki/Dev/Qubes_Remote_Support) - QubesOS to be remotely manageable from on-demand, ephemeral, hidden onion service to dom0/AdminVM.
*   [Qubes-Whonix development notes](https://www.whonix.org/wiki/Dev/Qubes) - Whonix development notes.
*   [Tips on Remaining Anonymous](https://www.whonix.org/wiki/DoNot#Use_Clearnet_and_Tor_at_the_Same_Time) - The wiki page provides guidelines and good habits for online privacy and security, with a focus on distinguishing between anonymity and pseudonymity.

### Anonymity

*   [i2p-Whonix](https://forum.qubes-os.org/t/temporary-way-to-run-i2p-on-qubes-whonix/15861) - Temporary way to run i2p on Qubes-Whonix.
*   [ipfs (⭐23k)](https://github.com/ipfs/ipfs) - A peer-to-peer hypermedia protocol to make the web faster, safer, and more open.
*   [LocalSend](https://forum.qubes-os.org/t/localsend-file-sharing-locally-with-wifi/29939) -Free, open-source app that allows you to securely share files and messages with nearby devices over your local network without needing an internet connection. Basically, a platform neutral “airdrop”.
*   [Lokinet](https://privsec.dev/posts/qubes/using-lokinet-on-qubes-os) - Lokinet is the reference implementation of LLARP (low latency anonymous routing protocol), a layer 3 onion routing protocol.
*   [Really disposable ram based qubes](https://forum.qubes-os.org/t/really-disposable-ram-based-qubes/21532) - You can use your QubesOS 𝚜𝚝𝚊𝚝𝚎𝚕𝚎𝚜𝚜 just like TailsOS, with persistent storage for VMs. That is pretty simple! It takes 6Gb of extra 𝚁𝙰𝙼 (for store root filesystem files).
*   [Whonix](https://www.whonix.org/wiki/Qubes) - Qubes-Whonix ™ is the seamless combination of Qubes OS and Whonix™ for advanced security and anonymity.
*   [How to bypass the GFW on Qubes OS when you’re in China](https://forum.qubes-os.org/t/how-to-bypass-the-gfw-on-qubes-os-when-youre-in-china-qubes-os/14957) - The purpose of this article is to provide several feasible ways to bypass the GFW for you to choose.
*   [Tailscale Setup](https://forum.qubes-os.org/t/tailscale-setup/19004) - How to create template and install Tailscale.

### Crypto

*   [Split Bitcoin Wallet (⭐258)](https://github.com/Qubes-Community/Contents/blob/master/docs/security/split-bitcoin.md) - A "split" bitcoin wallet is a strategy of protecting your bitcoin by having your wallet split into an offline "cold storage" wallet and an online "watching only" wallet.
*   [Split Monero Wallet](https://www.getmonero.org/resources/user-guides/cli_wallet_daemon_isolation_qubes_whonix.html) - With Qubes + Whonix you can have a Monero wallet that is without networking and running on a virtually isolated system from the Monero daemon which has all of its traffic forced over Tor.
*   [Awesome-DeSci (⭐110)](https://github.com/DeSciWorldDAO/awesome-desci) - A curated list of awesome Decentralized Science (DeSci) resources, projects, articles and more.
*   [Ultimate Guide on Using Trezor on Qubes](https://ursidaecyber.com/how-to-use-trezor-on-qubes-os/) - his guide explains how to use Trezor cryptocurrency hardware wallets on Qubes OS.

## Kernels

*   [eBPF](https://ebpf.io) - eBPF is a revolutionary technology with origins in the Linux kernel that can run sandboxed programs in an operating system kernel.
*   [Rump (⭐1.1k)](https://github.com/rumpkernel/rumprun) - Rump kernels enable you to build the software stack you need without forcing you to reinvent the wheels.

### Microkernels

*   [OpenXT](https://openxt.org/) - OpenXT is an open-source development toolkit for hardware-assisted security research and appliance integration.
*   [Qubes-linux-kernel (⭐92)](https://github.com/QubesOS/qubes-linux-kernel) - Qubes package for Linux kernel.
*   [seL4](https://sel4.systems/) - seL4 is a high-assurance, high-performance operating system microkernel.
    *   [makatea](https://trustworthy.systems/projects/TS/makatea) - Qubes OS like operating system but with seL4.

### Unikernels

*   [Awesome-Unikernels (⭐47)](https://github.com/uniqernel/awesome-unikernels) - Secure, lightweight and high performance approach to application delivery.
*   [ClickOS](http://cnp.neclab.eu/projects/clickos) - Efficient network function virtualization platform, optimized for Xen and developed by NEC.
*   [Clive](http://lsub.org/ls/clive.html) - Research project from Rey Juan Carlos University (Madrid), developed in Go.
*   [HaLVM](https://galois.com/project/halvm) - Port of Glasgow Haskell compiler producing Xen optimized unikernels.
*   [Mini-OS](https://wiki.xen.org/wiki/Mini-OS) - Reference kernel distributed with Xen.
*   [Qubes-Mirage-Firewall (⭐219)](https://github.com/mirage/qubes-mirage-firewall) - A unikernel that can run as a Qubes OS ProxyVM, replacing sys-firewall.
*   [Unikraft](https://unikraft.org/) - Unikraft powers the next-generation of cloud native applications by enabling you to radically customize and build custom OS/kernels, unlocking best-in-class performance, security primitives and efficiency savings.
*   [Unik (⭐2.7k)](https://github.com/solo-io/unik) - A platform for automating unikernel & MicroVM compilation and deployment.

### Unikernel-like

*   [Drawbridge](https://www.microsoft.com/en-us/research/project/drawbridge) - Research prototype platform from Microsoft.
*   [Graphene (⭐780)](https://github.com/oscarlab/graphene) - Library OS optimized for Intel SGX.

## Qubes OS Server

*   [Admin API](https://www.qubes-os.org/doc/admin-api/) - The goals of the Admin API system is to provide a way for the user to manage the domains without direct access to dom0.
*   [Ansible](https://qubes-ansible.readthedocs.io/en/latest/) - Automation with Ansible.
*   [Multi-user Qubes: Using sys-gui to make non-adminstrative user logins](https://forum.qubes-os.org/t/multi-user-qubes-using-sys-gui-to-make-non-adminstrative-user-logins/29967) - Here we try to create restricted sys-guis, where they only need to see the parts that pertain to them. Basically a administrative gui login (dom0), and a restricted user sys-gui login.
*   [Qubes-network-server (⭐112)](https://github.com/Rudd-O/qubes-network-server) - Turn your Qubes OS into a networking server.
*   [Qubes-remote-desktop (⭐9)](https://github.com/QubesOS-contrib/qubes-remote-desktop) - SystemD services for creating VNC server session in dom0 or any Qube.
*   [Qubes Admin Policies/API](https://forum.qubes-os.org/t/how-to-use-the-qubes-admin-policies-api-despite-the-lack-of-documentation-wip/29863/1) - The qubes admin policies are core to modern qubes.
*   [Qubes core admin client](https://www.qubes-os.org/doc/qubes-core-admin-client/) - Qubes core admin client’s documentation!
*   [Qubes core admin](https://www.qubes-os.org/doc/qubes-core-admin/) - Qubes core-admin’s documentation!
*   [Qubes core stack](https://www.qubes-os.org/doc/qubes-core-stack/) - Introducing the Next Generation Qubes Core Stack.
*   [Port forwarding](https://gist.github.com/fepitre/941d7161ae1150d90e15f778027e3248) - Qubes-os port forwarding to allow external connections
*   [ Opensnitch Nodes](https://forum.qubes-os.org/t/an-opensnitch-nodes-implementation-to-filter-outbound-traffic-from-multiple-qubes/29369) -A node is a daemon running on a machine. You can install the daemon on multiple machines, and manage them from the server
*   [Qubes sync git repositories with dom0](https://codeberg.org/brunoschroeder/qubes-git-syncer) - This solution is intended have git repos easily in sync with dom0.
*   [Salt (management software)](https://www.qubes-os.org/doc/salt/) - Salt allows administrators to easily configure their systems.
*   [Salt Beginner's Guide](https://forum.qubes-os.org/t/qubes-salt-beginners-guide/20126) - Guide for beginners who enjoy an hands-on introduction with examples.
*   [qubes-mgmt-salt-dom0-qvm (⭐15)](https://github.com/QubesOS/qubes-mgmt-salt-dom0-qvm#readme) - Salt can manage many Qubes settings via the qvm state module.
*   [Virtual Machine Formulae](https://www.qubes-os.org/doc/salt/#virtual-machine-formulae) - Salt allows administrators to easily configure their systems. In this guide we will show how it is set up and how you can modify it for your own purpose.
*   [Configuration Management](https://docs.gonzalobulnes.com/configuration_management.html) - A collection of guides about creating Salt formulas in Qubes OS and distributing them as RPM packages to take advantage of the secure updates mechanism for dom0.
*   [Offcial Salt Documentation](https://docs.saltproject.io/en/latest/contents.html) - Salt is an event-driven automation tool and framework to deploy, configure, and manage complex IT systems.
*   [Official Salt User Guide](https://docs.saltproject.io/salt/user-guide/en/latest/index.html) - Salt user guide
*   [qusal (⭐27)](https://github.com/ben-grande/qusal) - Salt Formulas for Qubes OS.
*   [qvm-firewall](https://dev.qubes-os.org/projects/core-admin-client/en/latest/manpages/qvm-firewall.html) - Manage VM outbound firewall.
*   [Qubes Admin python modules](https://dev.qubes-os.org/projects/core-admin-client/en/latest/py-modindex.html) - Python Module Index
*   [Qubes network dom0 display](https://forum.qubes-os.org/t/simple-qubes-os-qubes-network-display/26031) - a simple script to run in dom0 (easy to audit) that will output a hierarchy tree of netvm and their qubes.
*   [Colored! network information](https://forum.qubes-os.org/t/colored-network-information-iptables-routes-addresses-shell-reporting-networking/22258/1) - Colorful network information with iptables & ip.
*   [Visualize Qubes Configuration Without Trust](https://forum.qubes-os.org/t/visualize-qubes-configuration-without-trust-a-use-case-for-the-qubes-admin-api/23072) - Visualize Qubes Configuration with the Qubes Admin API.
*   [SSH or VNC into Qubes dom0](https://www.whonix.org/wiki/Remote_Administration#Qubes_-_SSH_or_VNC_into_Qubes_dom0) - tutorial on how to SSH or VNC in to dom0
*   [qubes-remote-support-receiver dom0 scripts (⭐4)](https://github.com/QubesOS/qubes-remote-support) - Scripts to configure dom0 to allow remote connections.
*   [Web VNC](https://forum.qubes-os.org/t/remote-qubes-user-testing-running-qubes-in-the-browser/13817) - Running Qubes in the Browser
*   [VNC (⭐9)](https://github.com/QubesOS-contrib/qubes-remote-desktop) - SystemD services for creating VNC server session in dom0 or any qube.
*   [Software RAID (mdadm) Qubes Installation Procedure](https://forum.qubes-os.org/t/software-raid-mdadm-qubes-installation-procedure-wip/27886) - CLI & Software Raid installation procedure.
*   [borg-offsite-backup (⭐4)](https://github.com/Rudd-O/borg-offsite-backup) - help back up Qubes VMs and ZFS file systems.

## Exploitation Tools

*   [Awesome-Fuzzing (⭐884)](https://github.com/cpuu/awesome-fuzzing) - A curated list of references to awesome Fuzzing for security testing. Additionally there is a collection of freely available academic papers, tools and so on.
*   [AFL++ (⭐5.7k)](https://github.com/AFLplusplus/AFLplusplus) - AFL++ is a superior fork to Google's AFL - more speed, more and better mutations, more and better instrumentation, custom module support, etc.
*   [Bonzai (⭐225)](https://github.com/rwxrob/bonzai) - It's like a modular, multicall BusyBox builder for Go with built in completion and embedded documentation support.
*   [CodeQL](https://codeql.github.com/) - Discover vulnerabilities across a codebase with CodeQL.
*   [Joern (⭐2.4k)](https://github.com/joernio/joern) - Joern is a platform for analyzing source code, bytecode, and binary executables. It generates code property graphs (CPGs), a graph representation of code for cross-language code analysis.
*   [Hyperdbg (⭐3.2k)](https://github.com/HyperDbg/HyperDbg) - HyperDbg Debugger is an open-source, community-driven, hypervisor-assisted, user-mode, and kernel-mode Windows debugger with a focus on using modern hardware technologies. It is a debugger designed for analyzing, fuzzing, and reversing.
*   [LeechCore (⭐607)](https://github.com/ufrisk/LeechCore) - The LeechCore Memory Acquisition Library focuses on Physical Memory Acquisition using various hardware and software based methods.
    *   [LeechCore-Plugins (⭐35)](https://github.com/ufrisk/LeechCore-plugins) - This repository contains various plugins for LeechCore - Physical Memory Acquisition Library.
*   [Libvmi](https://libvmi.com/) - LibVMI is a C library with Python bindings that makes it easy to monitor the low-level details of a running virtual machine.
*   [Lldb](https://lldb.llvm.org/) - LLDB is a next generation, high-performance debugger.
*   [Memflow (⭐852)](https://github.com/memflow/memflow) - memflow is a library that enables introspection of various machines (hardware, virtual machines, memory dumps) in a generic fashion.
*   [Capstone](https://www.capstone-engine.org/) - Capstone is a lightweight multi-platform, multi-architecture disassembly framework.
*   [Coredump (⭐7)](https://github.com/memflow/memflow-coredump) - Access Microsoft Windows Coredump files.
*   [Kvm (⭐40)](https://github.com/memflow/memflow-kvm) - KVM memflow connector.
*   [Pcileech (⭐24)](https://github.com/memflow/memflow-pcileech) - Access pcileech interface.
*   [sys-mitm (⭐40)](https://github.com/ClaraCrazy/qubes-docs/blob/main/sys-mitm.md) - A man-in-the-middle Qube for your traffic analysis needs.
*   [Qemu\_procfs (⭐40)](https://github.com/memflow/memflow-qemu-procfs) - Access QEMU Physical memory.
*   [Unicorn](https://www.unicorn-engine.org/) - Unicorn is a lightweight multi-platform, multi-architecture CPU emulator framework.
*   [MemProcFS (⭐3.5k)](https://github.com/ufrisk/MemProcFS) - MemProcFS is an easy and convenient way of viewing physical memory as files in a virtual file system.
    *   [MemProcFS-Plugins (⭐54)](https://github.com/ufrisk/MemProcFS-plugins) - This repository contains various non-core plugins for MemProcFS - The Memory Process File System.
*   [Microlibvmi (⭐176)](https://github.com/Wenzel/libmicrovmi) - A cross-platform unified Virtual Machine Introspection API library.
*   [Radare2 (⭐22k)](https://github.com/radareorg/radare2) - Libre Reversing Framework for Unix Geeks.
*   [Volatility3 (⭐3.1k)](https://github.com/volatilityfoundation/volatility3) - Volatility is the world's most widely used framework for extracting digital artifacts from volatile memory (RAM) samples.

### Xen Exploitation

*   [Advanced Exploitation](https://www.youtube.com/watch?v=6Ld5CiInrcI) - Xen Hypervisor VM Escape
*   [Blackhat 2010 ](https://www.youtube.com/watch?v=sTC9x5hYYFo) - Hacking the Hypervisor
*   [Blackhat 2014](https://www.youtube.com/watch?v=PJWJjb0uxXE) - [\[Website Slides\]](https://www.blackhat.com/docs/eu-14/materials/eu-14-Wojtczuk-Lessons-Learned-From-Eight-Years-Of-Breaking-Hypervisors.pdf) - Lessons Learned from Eight Years of Breaking Hypervisors
*   [Blackhat 2015](https://www.youtube.com/watch?v=nyW3eTobXAI) - [\[PDF Slides\]](http://c7zero.info/stuff/AttackingHypervisorsViaFirmware_bhusa15_dc23.pdf) - Attacking Hypervisors Using Firmware And Hardware
*   [Ouroboros](https://www.youtube.com/watch?v=kt3kX94kWcM) - Tearing Xen Hypervisor With the Snake
*   [Software Attacks on Hypervisor Emulation of Hardware](https://www.youtube.com/watch?v=c4DnlP88D2Y) - [\[PDF Slides\]](https://www.troopers.de/downloads/troopers17/TR17_Attacking_hypervisor_through_hardwear_emulation.pdf)
*   [The Arms Race Over Virtualization](https://www.youtube.com/watch?v=nWvg7NKwOjg) - [\[PDF Slides\]](https://www.blackhat.com/docs/us-16/materials/us-16-Luan-Ouroboros-Tearing-Xen-Hypervisor-With-The-Snake.pdf)
*   [XenPwn](https://www.youtube.com/watch?v=qxz8MzE3QME) - [\[PDF Slide\]](https://www.blackhat.com/docs/us-16/materials/us-16-Wilhelm-Xenpwn-Breaking-Paravirtualized-Devices-wp.pdf) - Breaking Paravirtualized Devices
*   [Hypervisor Vulnerability Research \[PDF\]](https://alisa.sh/slides/HypervisorVulnerabilityResearch2020.pdf) - State of the Art

### Web articles

*   [Glitches in the Matrix](https://www.cpl0.com/blog/?p=46) - Escape via NMI
*   [Xen exploitation part 1: XSA-105](https://blog.quarkslab.com/xen-exploitation-part-1-xsa-105-from-nobody-to-root.html) - From nobody to root
*   [Xen exploitation part 2: XSA-148](https://blog.quarkslab.com/xen-exploitation-part-2-xsa-148-from-guest-to-host.html) - From guest to host

## Optics and Extra Info

### Qubes OS Summit - 3mdeb Summit videos

*   [Qubes OS Summit 2024](https://youtu.be/lJFxtdan9qY?list=PLuISieMwVBpJmIaHgyv7yKDwrHpqym9Qh) - Day 1
*   [Qubes OS Summit 2024](https://youtu.be/9AkBeBwxdA0?list=PLuISieMwVBpL5S7kPUHKenoFj_YJ8Y0_d) - Day 2
*   [Qubes OS Summit 2023](https://www.youtube.com/watch?v=_UxndcxIngw) - Day 1
*   [Qubes OS Summit 2023](https://www.youtube.com/watch?v=xo2BVTn7ohs) - Day 2
*   [Qubes OS summit 2022](https://www.youtube.com/watch?v=hkWWz3xGqS8) - Day 1
*   [Qubes OS summit 2022](https://www.youtube.com/watch?v=A9GrlQsQc7Q) - Day 2
*   [Qubes OS-3mdeb mini-summit 2021](https://www.youtube.com/watch?v=y3V_V0Vllas) - Day 1
*   [Qubes OS-3mdeb mini-summit 2021](https://www.youtube.com/watch?v=KdDr6TiqF0k) - Day 2

### Xen project summit 2024 videos

*   [Demi Marie Obenour: Reasonably Secure GPU Acceleration](https://youtu.be/FrKEUVB-BYM?list=PLQMQQsKgvLntZiKoELFs22Mtk-tBNNOMJ)
*   [Marek Marczykowski-Górecki: Host and Guest Suspend Under Xen - S3 and S0ix](https://youtu.be/4UUEt4rll6U?list=PLQMQQsKgvLntZiKoELFs22Mtk-tBNNOMJ)
*   [Marek Marczykowski-Górecki: Linux Stubdomains Status Update](https://youtu.be/3Lg5iTmXl-I?list=PLQMQQsKgvLntZiKoELFs22Mtk-tBNNOMJ)
*   [Full xen project summit 2024 playlist](https://www.youtube.com/playlist?list=PLQMQQsKgvLntZiKoELFs22Mtk-tBNNOMJ)

### UX - User Experience

*   [UX Bessie](https://vimeo.com/542041258) - Qubes OS AppMenu Design Direction. Part of 2020/21 MOSS funded UX work.
*   [UX Jackie](https://vimeo.com/541946756) - Qubes OS AppMenu Design Direction. Part of 2020/21 MOSS funded UX work.

### Extra Info

*   [3mdeb](https://3mdeb.com/) - We’re hands-on firmware experts with years of experience writing elegant, scalable and custom code for clients.
*   [Hipervisor From Scratch (⭐2.3k)](https://github.com/SinaKarvandi/Hypervisor-From-Scratch)- Source code of a multiple series of tutorials about the hypervisor.
*   [GPU Virtual Machine (GVM)](https://www.youtube.com/watch?v=YllX-ud70Nk)  - An OpenMdev Project (Qubes OS Summit 2022)
*   [Micah Lee presents](https://livestream.com/accounts/9197973/events/8286152/videos/178431606) - “Qubes OS: The Operating System That Can Protect You Even If You Get Hacked”
*   [Explaining Computers presents](https://www.youtube.com/watch?v=hWDvS_Mp6gc) - “Qubes OS: Security Oriented Operating System”
*   [Backups in Qubes](https://forum.qubes-os.org/t/backups-in-qubes-video/23234) - Learn how and why to back up your data on Qubes OS.

## Training and Materials

*   [Training-materials (⭐5)](https://github.com/QubesOS/training-materials/) - A Collection of training materials for Qubes OS.
    -[Qubes for Journalists (⭐19)](https://github.com/kennethrrosen/qubes-for-journalists/) - Existing guides and infrastructure for journalists insufficiently prepares them for digitally interacting with sources, working on sensitive stories while protecting sensitive materials offline and online, and traveling cross borders with personal and professional data.
*   [Qubes-diagrams (⭐16)](https://github.com/rootkovska/qubes-diagrams) - Qubes OS architecture diagrams.
*   [Qubes-artwork (⭐14)](https://github.com/QubesOS/qubes-artwork) - This repository contains various artworks for Qubes OS.
*   [pwn.college](https://pwn.college/) - pwn.college is an education platform for students (and other interested parties) to learn about, and practice, core cybersecurity concepts in a hands-on fashion.
*   [Anonymous Planet](https://anonymousplanet.org) - The Hitchhiker’s Guide to Online Anonymity: the comprehensive guide for online anonymity and OpSec.
    *   [Anonymous Planet Onion](http://thgtoa27ujspeqxasrfvcf5aozqdczvgmwgorrmblh6jn4nino3spcqd.onion/) - For those who wish to read over the anonymous Tor network.
    *   [Privacy-Security-Anonymity Matrix Space](https://psa.anonymousplanet.org/) - The place to be for all topics regarding privacy, anonymity and other subjects. Rooms are click-to-join.
*   [The Book of Secret Knowledge (⭐168k)](https://github.com/trimstray/the-book-of-secret-knowledge) - A collection of inspiring lists, manuals, cheatsheets, blogs, hacks, one-liners, cli/web tools, and more.
*   [Qubes OS for Anarchists](https://www.anarsec.guide/posts/qubes/) - Qubes OS for Anarchists | Guide & Best Practices
*   [The Guardian's Deep Dive into Qubes OS: a Secure Solution for Whistleblowing and Journalism](https://www.infoq.com/news/2024/05/the-guardian-quebes-os/?ref=dailydev) - The Guardian's engineering team recently shared their experience with Qubes OS, a security-focused desktop operating system.
*   [Free e-book Foundation](https://ebookfoundation.github.io/) - Free ebooks to help your journey!

## Companies using Qubes OS

*   [Qubes Partners](https://www.qubes-os.org/partners/) - The Qubes Project relies greatly on the generous support of the organizations, companies, and individuals who have become Qubes Partners.

## Social media

The Qubes OS Project has a presence on the following social media platforms:

*   [ClubHouse](https://www.clubhouse.com/house/qubes-os) - Qubes OS Clubhouse Room
*   [Discord](https://discord.gg/YMUbTt7ZRG) - Qubes OS discord invite link
*   [Dread](http://g66ol3eb5ujdckzqqfmjsbpdjufmjd5nsgdipvxmsh7rckzlhywlzlqd.onion/d/Qubes) - Dark Net QubesOS .onion forum room.
*   [Facebook](https://www.facebook.com/QubesOS/) - Qubes OS facebook page
*   [Forum](https://forum.qubes-os.org/) - Qubes OS Discorse Forum
*   [LinkedIn](https://www.linkedin.com/company/qubes-os/) - Qubes OS linkedin account
*   [Mastodon](https://mastodon.social/@QubesOS) - Qubes OS Mastodon channel
*   [Matrix Discord Bridge](https://matrix.to/#/#qubes-os-discord-bridge-v2:matrix.org) - Qubes OS Discord General Room Bridge
*   [Matrix:Qubes OS](https://matrix.to/#/#cybersec-qubes_os:matrix.org) - General Qubes OS matrix room
*   [Reddit Qubes OS](https://www.reddit.com/r/Qubes/) - General Qubes OS Reddit room.
*   [Reddit hacking\_qubes\_os](https://www.reddit.com/r/hacking_qubes_os) - Reddit room dedicated to hacking Qubes OS
*   [Reddit hack\_with\_qubes\_os](https://www.reddit.com/r/hack_with_qubes_os) - Reddit room dedicated to hacking with Qubes OS
*   [Twitter](https://twitter.com/QubesOS) - Qubes OS Twitter account
*   `#xen`      channel on irc.oftc.net via traditional IRC clients.
*   `#qubes`    channel on irc.libera.chat via traditional IRC clients.
*   `#qubes-os` channel on irc.anonops.com via traditional IRC clients.

## Qubes OS Legends

*   [Joanna Rutkowska](https://en.wikipedia.org/wiki/Joanna_Rutkowska) - Founder of Qubes OS.
    *   [Blog](https://blog.invisiblethings.org/) - Personal Blog.
    *   [Subverting the Xen Hypervisor \[PDF\]](https://invisiblethingslab.com/resources/bh08/part1.pdf) - Xen 0wning Trilogy
        Part One
    *   [Preventing and Detecting Xen Hypervisor Subversions \[PDF\]](https://invisiblethingslab.com/resources/bh08/part2.pdf) - Xen 0wning Trilogy
        Part Two
    *   [Bluepilling the Xen Hypervisor \[PDF\]](https://invisiblethingslab.com/resources/bh08/part3.pdf) - Xen 0wning Trilogy Part Three
*   [Marek Marczykowski-Górecki](https://github.com/marmarek) - Lead developer at Qubes OS.
*   [Ninavizz](https://vimeo.com/user1589693) - Qubes OS UX Designer.
*   [Unman](https://github.com/unman?tab=repositories) - Qubes OS contributor.
    *   [Templates](https://qubes.3isec.org/Templates_4.2/) - Unman custom templates.
    *   [Install Scripts (⭐22)](https://github.com/unman/shaker) -  Unman install scripts
    *   [Notes (⭐41)](https://github.com/unman/notes) - a good reference
    *   [Shaker (⭐22)](https://github.com/unman/shaker) - Shaker!
*   [Core Team](https://www.qubes-os.org/team/#core-team) - Qubes OS core team.
*   [ClaraCrazy (⭐40)](https://github.com/claracrazy/qubes-docs) - Qubes Guru & Just amazing!.

## Releases

*   [Release notes](https://www.qubes-os.org/doc/releases/notes/) - Developer documentation Notes
*   [Release schedules](https://www.qubes-os.org/doc/releases/schedules/) -  Developer Release Schedules
*   [Supported releases](https://www.qubes-os.org/doc/supported-releases/) - This page details the level and period of support for releases of operating systems in the Qubes ecosystem.
*   [Testing new releases and updates](https://www.qubes-os.org/doc/testing/) - Testing new Qubes OS releases and updates is one of the most helpful ways in which you can contribute to the Qubes OS Project.

## Adventure Further

*   Adventures start here ---> [Adventure Here! (⭐357k)](https://github.com/sindresorhus/awesome) - All the awesome lists.
    **[⬆ back to top](#awesome-qubes-os-)**

`:|: ADVENTURE FURTHER :|: HACK ALL THE THINGS :|: TRUST NOTHING :|: WITH <3! ~X`

[![](https://img.shields.io/static/v1?label=Sponsor\&message=%E2%9D%A4\&logo=GitHub\&color=%23fe8e86)](https://github.com/sponsors/xn0px90)

## Contributing

Contribution guidelines can be found [here (⭐109)](https://github.com/xn0px90/Awesome-Qubes-OS/blob/master/CONTRIBUTING.md).

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/1.0/88x31.png)](https://creativecommons.org/licenses/by/1.0/)

This work is licensed under a [Creative Commons Attribution 1.0 Generic](http://creativecommons.org/licenses/by/1.0/).

