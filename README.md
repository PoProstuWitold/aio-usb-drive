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
- [![Windows 11][Windows11_SHIELD]][Windows11_LINK]
- [![Windows 10][Windows10_SHIELD]][Windows10_LINK]
- [![Windows 10 LTSC][Windows10_LTSC_SHIELD]][Windows10_LTSC_LINK]
- [![Windows PE][WindowsPE_SHIELD]][WindowsPE_LINK]

### Linux
- Mint
- Debian
- EndeavourOS
- Ubuntu
- Fedora (KDE)
- Fedora (Gnome)
- Zorin
- openSUSE Tumbleweed
- NixOS
- Arch
- AlmaLinux
- Kali
- Void
- Quebes

### Other
- OpenBSD
- FreeBSD
- TempleOS

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

Project Link: [https://github.com/poprostuwitold/aio-usb-drive](https://github.com/poprostuwitold/aio-usb-drive)

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
[Windows10_LTSC_SHIELD]: https://img.shields.io/badge/Windows_10_LTSC-0078D6?style=for-the-badge&logo=windows&logoColor=white

<!-- Other -->

<!-- LINKS -->
<!-- ISOs -->
[Windows11_LINK]: https://www.microsoft.com/en-us/software-download/windows11
[Windows10_LINK]: https://www.microsoft.com/en-us/software-download/windows10
[WindowsPE_LINK]: https://learn.microsoft.com/pl-pl/windows-hardware/manufacture/desktop/download-winpe--windows-pe?view=windows-11
[Windows10_LTSC_LINK]: https://learn.microsoft.com/en-us/windows/whats-new/ltsc/whats-new-windows-10-2021

<!-- Other -->
[Ventoy_LINK]: https://www.ventoy.net/en/index.html
