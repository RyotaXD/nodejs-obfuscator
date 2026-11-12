# 💀 NODEJS-OBFUSCATOR 

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-Raccoon%20Engine-green?style=for-the-badge&logo=nodedotjs" alt="Node.js">
  <img src="https://img.shields.io/badge/Obfuscation-Extreme%20Chaos-red?style=for-the-badge" alt="Obfuscation">
  <img src="https://img.shields.io/badge/Platform-Termux%20%2F%20Linux-blue?style=for-the-badge&logo=linux" alt="Platform">
</p>

> **NODEJS-OBFUSCATOR** adalah obfuscator dan runner skrip Node.js tingkat lanjut yang dirancang khusus untuk melindungi sourcecode dari decompiler, reverse engineering *script kiddies*. Dilengkapi dengan enkripsi AES-256, Masking, struktur multi-layer, serta 1000+ baris *padding trap* untuk melumpuhkan analisis statis.

---

## 🚀 Fitur Utama

- 🛡️ **AES-256 + XOR Dual-Layer Encryption**: Payload utama dikunci rapat menggunakan enkripsi tingkat militer dan dimask ulang dengan bitwise XOR.
- 🧬 **AST Distortion & Dead-Code Injection**: Memanipulasi *Abstract Syntax Tree* (AST) dan menyuntikkan ribuan baris kode sampah agar struktur aslinya hancur total.
- 📦 **Massive 1000+ Lines Padding**: Secara otomatis mendilatasi ukuran file runner hingga ribuan baris untuk membuat analis pusing tujuh keliling.
- ⚡ **Zero-Trace Scope Binding**: Eksekusi runtime langsung disuntikkan ke dalam memori tanpa meninggalkan variabel penampung string yang bisa di-dump.
- 📱 **Termux & Linux Native**: Dioptimalkan sepenuhnya agar berjalan lancar tanpa *Heap Out of Memory* (OOM) di perangkat mobile berbasis Termux.

---

## 🛠️ Persyaratan Sistem

Sebelum menjalankan tool ini, pastikan perangkat lu sudah menginstal:
* [Node.js](https://nodejs.org/) (Versi 18+ direkomendasikan, diuji pada Node v24)
* NPM (Node Package Manager)

---

## 📥 Cara Instalasi

Clone repositori ini atau masukkan file builder (`obf.js`) ke dalam direktori project lu:

```bash
# Clone repository
git clone https://github.com/RyotaXD/nodejs-obfuscator
cd nodejs-obfuscator
npm start
atau node obf.js

# Install dependencies yang dibutuhkan
npm install
