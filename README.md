# Desktop Hardware Maintenance & Windows 10 Clean Deployment

A comprehensive, three-stage walkthrough demonstrating physical hardware maintenance, bootable installation media preparation, and a fresh operating system deployment on a new 1TB SSD.

---

## 📌 Project Overview

This project documents the end-to-end rejuvenation and operating system setup of a desktop system. It serves as a practical demonstration of hardware troubleshooting, thermal maintenance, component replacement, and OS installation procedures.

### Key Highlights:
- Safe CPU thermal maintenance and heatsink servicing
- Storage modernization via high-capacity SSD installation
- Windows 10 Bootable Media creation using official deployment utilities
- BIOS boot order configuration, disk partitioning, and fresh OS installation

---

## 🛠️ Tools & Materials Used

* **Hardware & Consumables:**
  * Isopropyl alcohol (90%+) & lint-free microfiber wipes
  * High-performance thermal paste
  * New 1TB Solid State Drive (SATA / NVMe)
  * Phillips-head precision screwdriver
* **Software & Media:**
  * USB Flash Drive / SD Card (8GB+ capacity)
  * Windows 10 Media Creation Tool (ISO / USB creation)

---

## 📺 Project Stages & Video Walkthroughs

### Stage 1: Physical Maintenance & Component Upgrade
Focuses on safe component disassembly, thermal interface cleaning, and storage installation.

* **Procedures Covered:**
  * Static electricity precautions and case opening
  * Heatsink removal and old thermal paste cleaning using isopropyl alcohol
  * Reapplication of thermal paste (pea/dot method) and heatsink remounting
  * Removal of the legacy drive and installation of the new 1TB SSD
* 🎥 **[Watch Stage 1 Video Walkthrough](INSERT_YOUR_VIDEO_1_LINK_HERE)** In process...

---

### Stage 2: Windows 10 Bootable Media Creation
Demonstrates the digital preparation necessary to deploy an OS on unformatted storage.

* **Procedures Covered:**
  * Formatting and preparing the external media (Flash Drive / SD Card)
  * Utilizing the Windows Media Creation Tool to flash the ISO image
  * Verifying partition scheme and boot media integrity
* 🎥 **[Watch Stage 2 Video Walkthrough](https://www.youtube.com/watch?v=khKhPWUSp_I))**

---

### Stage 3: BIOS Configuration & Clean OS Installation
Walks through booting the system from external media, partitioning the new drive, and completing initial setup.

* **Procedures Covered:**
  * Accessing BIOS/UEFI settings and configuring boot priority
  * Initializing and selecting the new unallocated 1TB SSD in the Windows Setup installer
  * Completing the Out-of-Box Experience (OOBE), user account setup, and initial network/driver checks
* 🎥 **[Watch Stage 3 Video Walkthrough](INSERT_YOUR_VIDEO_3_LINK_HERE)**  In process...

---

## 📋 Post-Installation Checklist

- [ ] Run Windows Update until fully up-to-date
- [ ] Check Device Manager for missing hardware drivers (Chipset, GPU, Network)
- [ ] Verify disk allocation in `diskmgmt.msc`
- [ ] Monitor CPU idle and load temperatures to verify thermal paste efficacy
