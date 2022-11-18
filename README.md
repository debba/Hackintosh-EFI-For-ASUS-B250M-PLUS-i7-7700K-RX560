# Hackintosh-EFI-For-ASUS-B250M-i7-7700K-RX560

# # Introduction

My personal OpenCore configuration for running Hackintosh (MacOs Ventura) on my Asus B250M Plus and i7 7700K.
It contains patchers for AMD RX560 and is able to boot Arch Linux.

# # Update

- 2022-11-18

  - OC 0.8.6
  - Update KEXT regularly
  - Support Ventura 13.0.1

- 2022-11-18
  - Initial upload

# # Configuration

- CPU: i7-7700K
- Memory: 32GB DRR4
- Graphics card: AMD Radeon RX 560 Series 4GB

# # The Bios Settings

(Refer to the following general options for Settings)

### Disable

- Fast Boot
- Secure Boot
- Serial/COM Port
- Parallel Port
- VT-d
- CSM
- Thunderbolt
- Intel SGX
- Intel Platform Trust
- CFG Lock

### Enable

- VT-x
- Above 4G decoding
- Hyper-Threading
- Execute Disable Bit
- EHCI/XHCI Hand-off
- OS Type: Windows 8.1/10 UEFI Mode
- DVMT Pre-Allocated(iGPU Memory): 64MB
- SATA Mode: AHCI

## Working status

### Work normally:

- The sound card
- The network card
- App store
- Sleep
- H.264, HEVC hardware decoding, encoding, video processing
- SATA SSD Trim (terminal input: sudo Trimforce Enable)

## Instructions for use

- Copy the EFI folder and apply your changes

# # Thanks To

- [zsyshuyang](https://github.com/zsyshuyang/Hackintosh-EFI-For-ASUS-B250M-PLUS-i5-7500-RX580)
- [acidanthera](https://github.com/acidanthera)
- [daliansky](https://github.com/daliansky/)
- [Mrliu12123](http://bbs.pcbeta.com/viewthread-1851046-1-1.html)
