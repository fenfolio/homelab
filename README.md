# HomeLab Workstation Setup
Step-by-step guide to setting up a HomeLab Workstation for cybersecurity and forensic analysis. This setup covers installing VMware Workstation Pro, configuring a Windows environment, enabling Windows Subsystem for Linux (WSL), and installing essential forensic tools.

## Prerequisites
- 16GB RAM, SSD, multi-core processor
- VMware Workstation Pro 17 – [Download from VMware](https://www.vmware.com/products/workstation-pro.html)
- Windows 10 ISO – [Download from Microsoft](https://www.microsoft.com/en-us/software-download/windows10)
- Windows Server 2019 ISO – [Download from Microsoft](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2019)
- Ububtu Distribution - [Download from Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install-manual#downloading-distributions)
- Internet connection

## Step 1: Install VMware Workstation 17 Pro
- Signup to download [VMware Workstation Pro](https://www.vmware.com/products/workstation-pro.html)
- Follow on-screen instructions
- Restart if required

## Step 2: Setup Windows Environment
- Download [Windows 10 ISO](https://www.microsoft.com/en-ca/software-download/windows10)
- Download [Windows Server 2019 VM](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019)

## Step 3: Enable WSL & Install Ubuntu
- Run `wsl --install` in PowerShell (Admin)
- Restart and install Ubuntu from Microsoft Store
- Run:
  ```bash
  sudo apt update && sudo apt upgrade -y

## **Forensic Tools**
Below is a list of essential forensic tools to install after setting up your workstation:

| Tool | Description | Download Link |
|------|------------|--------------|
| Autopsy | Open-source digital forensic platform | [Download](https://www.autopsy.com/download/) |
| FTK Imager | Disk imaging tool | [Download](https://accessdata.com/products-services/forensic-toolkit-ftk) |
| Wireshark | Network traffic analysis tool | [Download](https://www.wireshark.org/download.html) |
| Volatility | Memory forensics framework | [Download](https://www.volatilityfoundation.org/) |
| Sysinternals Suite | Windows diagnostic and forensic tools | [Download](https://docs.microsoft.com/en-us/sysinternals/downloads/) |
| Hashcat | Password recovery tool | [Download](https://hashcat.net/hashcat/) |


