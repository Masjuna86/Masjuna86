<div align="center">
  <!-- GANTI 'images/banner-jaka-noc.png' DI BAWAH INI DENGAN JALUR GAMBAR ANDA -->
  <img src="images/banner-images/JLA JPG.jpg" alt="Jaka Lintas Akses NOC Banner" width="100%">

  <h1>NOC ISP Automation & Management</h1>
  <p><b>Kumpulan Script, Konfigurasi Terpusat, dan Otomatisasi untuk Network Operations Center</b></p>

  <!-- Badges Fokus MikroTik, OLT, DNS, dan Routing -->
  <img src="https://img.shields.io/badge/MikroTik-RouterOS-red.svg" alt="MikroTik">
  <img src="https://img.shields.io/badge/Network-DNS_&_Firewall-blue.svg" alt="DNS">
  <img src="https://img.shields.io/badge/Network-Routing_&_Failover-success.svg" alt="Routing">
  <img src="https://img.shields.io/badge/Hardware-OLT_ZTE_C300-brightgreen.svg" alt="OLT ZTE">
</div>

---

## About

Repositori ini berisi kumpulan skrip konfigurasi, aturan *routing*, dan alat manajemen jaringan yang dirancang khusus untuk kebutuhan operasional harian **Network Operations Center (NOC) Jaka Lintas Akses**.

Fokus utama dari dokumentasi dan konfigurasi di sini adalah untuk mengotomatiskan tugas-tugas teknis tingkat lanjut, menjaga stabilitas koneksi melalui penanganan *failover* yang presisi, serta memberikan visibilitas trafik langsung pada tingkat infrastruktur inti (Router MikroTik dan OLT).

---

## Core Features & Operations

### ⚙️ Routing, Failover, & Bandwidth
*   **Automated Failover Switching:** Skrip kustom untuk memantau status jaringan dan mengeksekusi peralihan koneksi secara otomatis menyilang ke berbagai *input ether* guna meminimalisir *downtime*.
*   **Traffic Routing:** Aturan *routing* spesifik untuk mengarahkan, memisahkan, dan memprioritaskan trafik jaringan (seperti pengujian *bandwidth*).
*   **Bandwidth Control:** Manajemen alokasi limit perangkat dan distribusi trafik internet ke klien.

### 🛡️ Firewall & Network Diagnostics
*   **Real-time Tracking:** Implementasi *firewall raw rule script* tingkat lanjut untuk melacak dan memonitor alamat IP yang diakses, khususnya untuk mengatasi masalah konektivitas pada aplikasi diagnostik seluler.
*   **DNS Resolution:** Pengaturan DNS untuk mempercepat respon *query* di lingkungan ISP.

### 🔌 OLT ZTE & GPON Management
*   **Direct OLT Configuration:** Panduan dan baris perintah untuk berinteraksi langsung dengan sistem OLT ZTE C300.
*   **ONU Interface Management:** Eksekusi pembaruan konfigurasi secara presisi, termasuk eksekusi penghapusan (*delete*) registrasi ONU pada *slot interface* GPON tertentu untuk perbaikan jaringan klien.
