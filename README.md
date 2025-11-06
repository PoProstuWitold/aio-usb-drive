<a id="top"></a>

# All-In-One USB Drive

A powerful all-in-one bootable USB featuring multiple operating systems, recovery tools, and scripts. Ideal for system installation, maintenance, and tech tasks.

<!-- TABLE OF CONTENTS -->
<details>
  <summary><h3>Table of Contents</h3></summary>
  <ol>
    <li>
      <a href="#about">About</a>
    </li>
    <li>
      <a href="#systems-isos">Systems (ISOs)</a>
      <ul>
        <li><a href="#windows">Windows</a></li>
        <li><a href="#linux">Linux</a></li>
      </ul>
    </li>
    <li>
      <a href="#programs--tools">Programs & Tools</a>
      <ul>
        <li><a href="#system-rescue">System Rescue</a></li>
        <li><a href="#scripts">Scripts</a></li>
      </ul>
    </li>
    <li>
      <a href="#directory-structure">Directory Structure</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#setup-usb-drive">Setup USB Drive</a></li>
      </ul>
    </li>
    <li>
      <a href="#usage">Usage</a>
    </li>
    <li>
      <a href="#faq">FAQ</a>
    </li>
    <li>
      <a href="#license">License</a>
    </li>
    <li>
      <a href="#contact">Contact</a>
    </li>
    <li>
      <a href="#acknowledgments">Acknowledgments</a>
    </li>
  </ol>
</details>

---

## About

This project is a personal **All-In-One USB toolkit** created for system installation, rescue, and diagnostics.  
It runs on **Ventoy**, allowing you to boot directly from ISO files without extraction or re-flashing.  
Supports both **UEFI** and **Legacy BIOS**, using **GPT partitioning** and **exFAT** for maximum compatibility.

<p align="right">(<a href="#top">back to top</a>)</p>

---

## Systems (ISOs)

### Windows

|                          **Name**                         	|                                                    **Description**                                                   	|                                                            **ISO**                                                            	|
|:---------------------------------------------------------:	|:--------------------------------------------------------------------------------------------------------------------:	|:-----------------------------------------------------------------------------------------------------------------------------:	|
|     [![Windows 11][Windows11_SHIELD]][Windows11_LINK]     	| Microsoft’s latest OS with a modern design, improved performance, and strong integration with cloud and AI features. 	|                            [Download](https://massgrave.dev/windows_11_links)                            	|
|     [![Windows 10][Windows10_SHIELD]][Windows10_LINK]     	|         A stable and widely used version focused on compatibility, regular updates, and enterprise features.         	|                            [Download](https://massgrave.dev/windows_10_links)                            	|
| [![Windows LTSC][Windows_LTSC_SHIELD]][Windows_LTSC_LINK] 	|  A long-term support edition without unnecessary apps or frequent updates, ideal for business and embedded systems.  	|                                      [Download](https://massgrave.dev/windows_ltsc_links)                                     	|
|     [![Windows PE][WindowsPE_SHIELD]][WindowsPE_LINK]     	|        A lightweight preinstallation environment used for deploying, repairing, or recovering Windows systems.       	| [Download](https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/download-winpe--windows-pe?view=windows-11) 	|

### Linux

|                        **Name**                        	|                                                 **Description**                                                 	|                                 **ISO**                                	|
|:------------------------------------------------------:	|:---------------------------------------------------------------------------------------------------------------:	|:----------------------------------------------------------------------:	|
|            [![Mint][Mint_SHIELD]][Mint_LINK]           	| A beginner-friendly Ubuntu-based distro known for its simplicity, stability, and Windows-like Cinnamon desktop. 	|             [Download](https://linuxmint.com/download.php)             	|
|         [![Debian][Debian_SHIELD]][Debian_LINK]        	|        One of the oldest and most stable Linux distributions, the foundation for many others like Ubuntu.       	|               [Download](https://www.debian.org/distrib/)              	|
| [![EndeavourOS][EndeavourOS_SHIELD]][EndeavourOS_LINK] 	|        An Arch-based distro offering an easier installation while keeping a near-vanilla Arch experience.       	|                  [Download](https://endeavouros.com/)                  	|
|         [![Ubuntu][Ubuntu_SHIELD]][Ubuntu_LINK]        	|                A popular, user-friendly Debian-based distro widely used for desktops and servers.               	|                 [Download](https://ubuntu.com/desktop)                 	|
|         [![Fedora][Fedora_SHIELD]][Fedora_LINK]        	|                  A cutting-edge, Red Hat–backed distro showcasing the latest open-source tech.                  	|         [Download](https://www.fedoraproject.org/kde/download)         	|
|          [![Zorin][Zorin_SHIELD]][Zorin_LINK]          	|               A visually polished Ubuntu-based distro designed to attract Windows and macOS users.              	|               [Download](https://zorin.com/os/download/)               	|
|      [![openSUSE][openSUSE_SHIELD]][openSUSE_LINK]     	|         A robust distro with strong administrative tools like YaST, great for developers and sysadmins.         	| [Download](https://get.opensuse.org/tumbleweed/?type=desktop#download) 	|
|          [![NixOS][NixOS_SHIELD]][NixOS_LINK]          	|      A unique distro using declarative configuration and the Nix package manager for reproducible systems.      	|                 [Download](https://nixos.org/download/)                	|
|            [![Arch][Arch_SHIELD]][Arch_LINK]           	|                  A minimalist, rolling-release distro for advanced users who want full control.                 	|               [Download](https://archlinux.org/download/)              	|
|    [![AlmaLinux][AlmaLinux_SHIELD]][AlmaLinux_LINK]    	|                    A community-driven RHEL-compatible distro created as a CentOS replacement.                   	|            [Download](https://almalinux.org/get-almalinux/)            	|
|            [![Kali][Kali_SHIELD]][Kali_LINK]           	|                   A Debian-based distro tailored for penetration testing and digital forensics                  	|        [Download](https://www.kali.org/get-kali/#kali-platforms)       	|
|            [![Void][Void_SHIELD]][Void_LINK]           	|                An independent, lightweight distro using runit and the fast XBPS package manager.                	|               [Download](https://voidlinux.org/download/)              	|
|         [![Quebes][Quebes_SHIELD]][Quebes_LINK]        	|          A security-focused distro using Xen virtualization to isolate apps and tasks into separate VMs         	|             [Download](https://www.qubes-os.org/downloads/)            	|

<p align="right">(<a href="#top">back to top</a>)</p>

---

## Programs & Tools

### System Rescue
- SystemRescue
- Rescuezilla 
- Grml

### Scripts
- massgrave

<p align="right">(<a href="#top">back to top</a>)</p>

---

## Directory Structure

Example structure of your USB drive:

```
All-In-One USB
```

<p align="right">(<a href="#top">back to top</a>)</p>

---

## Getting Started

### Prerequisites
- USB drive **>= 64 GB** (recommended: 128 GB+ and USB 3.1 or higher).
- Installed [Ventoy][Ventoy_LINK].
- A computer supporting **UEFI** or **Legacy BIOS**.

### Setup USB Drive
1. Install Ventoy using **GPT + exFAT** configuration.  
2. Copy ISOs into `/ISOs/` or any folder structure you prefer.  
3. Add scripts, docs, and utilities.  

<p align="right">(<a href="#top">back to top</a>)</p>

---

## Usage

- Plug in the drive and boot from it (select in BIOS/UEFI boot menu).  
- Pick any ISO from the Ventoy menu to boot directly.  
- Use scripts and tools for maintenance, diagnostics, or setup tasks.

<p align="right">(<a href="#top">back to top</a>)</p>

---

## FAQ

**Q:** Can I store normal files too?  
**A:** Yes! exFAT allows you to use it like a normal USB drive.  

**Q:** Will it work on UEFI and BIOS?  
**A:** Yes, Ventoy supports both.  

**Q:** Can I just delete or replace ISOs?  
**A:** Yes, no reinstall needed. 

<p align="right">(<a href="#top">back to top</a>)</p>

---

## License

Distributed under the **[MIT License](https://opensource.org/license/mit)**.  
See the [**``LICENSE``**](LICENSE) file for details.

<p align="right">(<a href="#top">back to top</a>)</p>

---

## Contact

**Witold Zawada (PoProstuWitold)**  
- [witoldzawada.dev](https://witoldzawada.dev/)
- [GitHub](https://github.com/poprostuwitold)  
- [LinkedIn](https://www.linkedin.com/in/witoldzawada/)

Project Link: [https://github.com/PoProstuWitold/aio-usb-drive](https://github.com/PoProstuWitold/aio-usb-drive)

<p align="right">(<a href="#top">back to top</a>)</p>

---

## Acknowledgments

- [Ventoy][Ventoy_LINK]

<p align="right">(<a href="#top">back to top</a>)</p>

---

<!-- MARKDOWN SHIELDS & LINKS -->
<!-- SHIELDS -->
<!-- ISOs -->
[Windows11_SHIELD]: https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white
[Windows10_SHIELD]: https://img.shields.io/badge/Windows_10-00A4EF?style=for-the-badge&logo=windows&logoColor=white
[WindowsPE_SHIELD]: https://img.shields.io/badge/Windows_PE-0078D6?style=for-the-badge&logo=windows&logoColor=white
[Windows_LTSC_SHIELD]: https://img.shields.io/badge/Windows_LTSC-0078D6?style=for-the-badge&logo=windows&logoColor=white

[Mint_SHIELD]: https://img.shields.io/badge/Linux%20Mint-87CF3E?style=for-the-badge&logo=Linux%20Mint&logoColor=white
[Debian_SHIELD]: https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white
[EndeavourOS_SHIELD]: https://img.shields.io/badge/EndeavourOS-7F7FFF?style=for-the-badge&logo=endeavouros&logoColor=white
[Ubuntu_SHIELD]: https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white
[Fedora_SHIELD]: https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white
[Zorin_SHIELD]: https://img.shields.io/badge/-Zorin%20OS-%2310AAEB?style=for-the-badge&logo=zorin&logoColor=white
[openSUSE_SHIELD]: https://img.shields.io/badge/openSUSE-%2364B345?style=for-the-badge&logo=openSUSE&logoColor=white
[NixOS_SHIELD]: https://img.shields.io/badge/NIX-5277C3.svg?style=for-the-badge&logo=NixOS&logoColor=white
[Arch_SHIELD]: https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff&style=for-the-badge
[AlmaLinux_SHIELD]: https://img.shields.io/badge/AlmaLinux-000000?style=for-the-badge&logo=AlmaLinux&logoColor=white
[Kali_SHIELD]: https://img.shields.io/badge/Kali-268BEE?style=for-the-badge&logo=kalilinux&logoColor=white
[Void_SHIELD]: https://img.shields.io/badge/Void%20Linux-295340?style=for-the-badge&logo=void-linux&logoColor=white 
[Quebes_SHIELD]: https://img.shields.io/badge/Qubes%20OS-3874D8?style=for-the-badge&logo=Qubes-OS&logoColor=white

<!-- Other -->


<!-- LINKS -->
<!-- ISOs -->
[Windows11_LINK]: https://www.microsoft.com/en-us/software-download/windows11
[Windows10_LINK]: https://www.microsoft.com/en-us/software-download/windows10
[WindowsPE_LINK]: https://learn.microsoft.com/pl-pl/windows-hardware/manufacture/desktop/download-winpe--windows-pe?view=windows-11
[Windows_LTSC_LINK]: https://learn.microsoft.com/en-us/windows/whats-new/ltsc/whats-new-windows-10-2021

[Mint_LINK]: https://linuxmint.com/
[Debian_LINK]: https://www.debian.org/index.html
[EndeavourOS_LINK]: https://endeavouros.com/
[Ubuntu_LINK]: https://ubuntu.com/
[Fedora_LINK]: https://www.fedoraproject.org/
[Zorin_LINK]: https://zorin.com/
[openSUSE_LINK]: https://www.opensuse.org/
[NixOS_LINK]: https://nixos.org/
[Arch_LINK]: https://archlinux.org/
[AlmaLinux_LINK]: https://almalinux.org/
[Kali_LINK]: https://www.kali.org/
[Void_LINK]: https://voidlinux.org/
[Quebes_LINK]: https://www.qubes-os.org/

<!-- Other -->
[Ventoy_LINK]: https://www.ventoy.net/en/index.html
