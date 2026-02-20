# 🛡️ Windows Server Core: Active Directory & Security Hardening Lab

🚩 Project Overview

Proyek ini mendemonstrasikan implementasi Identity & Access Management (IAM) dan Infrastructure Hardening menggunakan Windows Server 2019 Core yang di-host di lingkungan Linux (Ubuntu/KVM). Fokus utama adalah efisiensi operasional melalui SSH/CLI dan penerapan prinsip Least Privilege.

🛠️ Tech Stack
    
    Host OS: Ubuntu 22.04 LTS
    Hypervisor: KVM/QEMU via Virt-Manager
    Guest OS: Windows Server 2019 Core (No-GUI)
    Management: PowerShell, OpenSSH Server, Bash

🚀 Implementation Phases

Phase 1: Secure Server Deployment
    
    Instalasi Windows Server 2019 Core untuk meminimalkan attack surface.
    Konfigurasi OpenSSH Server untuk manajemen remote yang aman dari host Linux.
    Menonaktifkan akses GUI dan hanya mengizinkan akses administratif melalui jalur terenkripsi (Port 22).

Phase 2: Active Directory & Identity Provisioning
    
    Deployment Active Directory Domain Services (AD DS) menggunakan PowerShell.
    Otomatisasi pembuatan Organizational Units (OU) untuk memisahkan departemen.
    Scripting otomatisasi pembuatan user dengan kebijakan Force Password Change pada login pertama untuk menjamin privasi pengguna.

## 📜 Documentation
Laporan Hardening lengkap dapat ditemukan di: [Hardening_Report.pdf](./docs/Hardening_Report.pdf)
    

