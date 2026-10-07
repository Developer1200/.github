# 🏢 Badan Pusat Statistik Provinsi Sumatera Utara (BPS Sumut)
### 🚀 Developer1200 - Tim Inovasi & Pengembang Sistem Terintegrasi ALUSI

<div align="center">

![BPS Sumut](https://img.shields.io/badge/Instansi-BPS_Provinsi_Sumatera_Utara-005B9C?style=for-the-badge&logo=gov&logoColor=white)
![ALUSI Portal](https://img.shields.io/badge/Project-ALUSI_Single_Gateway-0284C7?style=for-the-badge)
![Scrum Framework](https://img.shields.io/badge/Methodology-Scrum_Framework-FF6B6B?style=for-the-badge)
![Go](https://img.shields.io/badge/Backend-Go_1.23-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![React](https://img.shields.io/badge/Frontend-React_19_Vite-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Kotlin](https://img.shields.io/badge/Mobile-Kotlin_Compose-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

**Portal Resmi Ekosistem Aplikasi & Layanan Informasi Terintegrasi BPS Provinsi Sumatera Utara**

</div>

---

## 📖 Tentang Organisasi Developer1200

**Developer1200** adalah repositori resmi tim inovasi teknologi informasi Badan Pusat Statistik (BPS) Provinsi Sumatera Utara (Kode Satker: **1200**). Organisasi ini mengelola pengembangan **ALUSI (Anjungan Layanan Unggul Sistem Informasi)**, sebuah *Single Portal Gateway* terpusat yang menghubungkan seluruh aplikasi internal, statistik sektoral, layanan publik, dan dasbor eksekutif pimpinan di Sumatera Utara.

---

## 🗺️ Ekosistem Repositori Proyek ALUSI

| Repositori | Platform & Stack | Deskripsi & Tanggung Jawab Modul | Status Build |
| :--- | :--- | :--- | :--- |
| ⚙️ **[backend-alusi-go](https://github.com/Developer1200/backend-alusi-go)** | Go (Golang) 1.23 + Gin + PostgreSQL | Core RESTful API, Streaming Realtime Status (SSE), Auth SSO BPS Sumut, Worker Engine, Optimasi WebP/SVG Logo, & Audit Trail. | ![CI](https://github.com/Developer1200/backend-alusi-go/actions/workflows/ci.yml/badge.svg) |
| 🖥️ **[frontend-admin-panel](https://github.com/Developer1200/frontend-admin-panel)** | React 19 + Vite + Tailwind v4 + TanStack Router | Dasbor Administrasi & Eksekutif untuk Manajemen Katalog, Logo, Panduan FAQ, Matriks RBAC, Monitoring SLA, & Analitik. | ![CI](https://github.com/Developer1200/frontend-admin-panel/actions/workflows/ci.yml/badge.svg) |
| 🌐 **[frontend-portal-alusi](https://github.com/Developer1200/frontend-portal-alusi)** | React 19 + Tailwind v4 | Portal Publik Web untuk Pencarian Aplikasi Cerdas, Katalog Interaktif, Favorit, & Informasi Layanan BPS Sumut. | ![CI](https://github.com/Developer1200/frontend-portal-alusi/actions/workflows/ci.yml/badge.svg) |
| 📱 **[android-alusi](https://github.com/Developer1200/android-alusi)** | Kotlin + Jetpack Compose + Coroutines | Aplikasi Mobile Android Resmi ALUSI untuk Akses Cepat Katalog, Notifikasi Layanan, & Monitoring Status Sistem. | ![CI](https://github.com/Developer1200/android-alusi/actions/workflows/ci.yml/badge.svg) |

---

## 🌿 Standar Pengembangan & Alur Kerja Git

Seluruh proyek dalam organisasi Developer1200 menerapkan standar *Clean Code*, pengujian otomatis (CI/CD), serta alur kerja branch 3-tier:

```mermaid
flowchart LR
    A["Feature Branch<br><code>feat/ADM-01-...</code>"] -->|Husky Validation & PR| B["dev Branch<br><i>(Integration)</i>"]
    B -->|Sprint Demo Review| C["SAT Branch<br><i>(Acceptance Testing)</i>"]
    C -->|Production Deploy| D["main Branch<br><i>(Live Production)</i>"]
```

### Aturan Utama:
1. **Branch Hierarchy**:
   - `main`: Rilis Stabil Produksi.
   - `SAT`: System Acceptance Testing / Staging Demo Pimpinan.
   - `dev`: Pengembangan Aktif Programmer.
2. **Husky Git Hooks**: Menjamin format pesan commit standar (*Conventional Commits*) dan memverifikasi nama branch issue sebelum push disetujui.
3. **Papan Manajemen Proyek**: **ANJUNGAN LAYANAN UNGGUL SISTEM INFORMASI**.

---

## 📞 Kontak & Dukungan

* **Satuan Kerja**: BPS Provinsi Sumatera Utara (1200)
* **Alamat**: Jl. Asrama No. 179, Medan, Sumatera Utara
* **Website Resmi**: [sumut.bps.go.id](https://sumut.bps.go.id)
