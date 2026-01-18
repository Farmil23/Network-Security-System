
# 🛡️ Network Security System

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Status-Development-yellow?style=for-the-badge)]()
[![Author](https://img.shields.io/badge/Author-Farhan%20Kamil-orange?style=for-the-badge)]()

> **Proyek pengembangan sistem keamanan jaringan berbasis Python dengan arsitektur modular dan manajemen error yang terpusat.**

Repositori ini berisi implementasi *backend* untuk sistem Network Security, yang dirancang dengan prinsip **Clean Code** dan **Modular Programming**. Struktur proyek ini disiapkan untuk dapat dikembangkan lebih lanjut menjadi pipeline Machine Learning atau aplikasi keamanan berskala besar.

---

## 👨‍💻 Author

**Nama** : Farhan Kamil Hermansyah  
**NRP** : 152024150  
**Peran** : Lead Developer & Maintainer

---

## 🏗️ Struktur Proyek

Proyek ini dibangun sebagai sebuah *Python Package* agar mudah didistribusikan dan diintegrasikan. Berikut adalah struktur folder utamanya:

```bash
networksecurity/
├── networksecurity/        # Source Code Utama (Package)
│   ├── exception/          # Custom Exception Handling
│   │   └── exception.py    # Script penanganan error kustom
│   ├── logging/            # Sistem Pencatatan Log
│   │   └── logger.py       # Konfigurasi logging terpusat
│   └── __init__.py
├── logs/                   # Direktori penyimpanan file log eksekusi
├── setup.py                # Konfigurasi instalasi paket
├── requirements.txt        # Daftar dependensi library
└── README.md               # Dokumentasi Proyek

```

## ✨ Fitur Utama (Core Features)

### 1. 📝 Centralized Logging System

Mengimplementasikan sistem pencatatan (*logging*) kustom yang secara otomatis menyimpan riwayat eksekusi program ke dalam folder `logs/`.

* **Manfaat**: Memudahkan *debugging* dan pelacakan aktivitas sistem secara *real-time*.
* **Format**: Waktu, Level Log, Pesan.

### 2. ⚠️ Custom Exception Handling

Menangani *error* sistem dengan mekanisme pembungkus (*wrapper*) kustom.

* **Manfaat**: Memberikan pesan error yang lebih deskriptif (termasuk nama file dan nomor baris) dibandingkan pesan error standar Python, sehingga mempercepat proses perbaikan *bug*.

### 3. 📦 Packaging Standard

Menggunakan `setup.py` untuk mendefinisikan proyek sebagai paket standar Python.

* **Manfaat**: Memungkinkan proyek diinstal sebagai library menggunakan `pip install -e .` dan memudahkan manajemen dependensi.

---

## 🚀 Cara Instalasi dan Menjalankan

Ikuti langkah-langkah berikut untuk menjalankan proyek di lingkungan lokal Anda:

### 1. Clone Repositori

```bash
git clone [https://github.com/username-anda/networksecurity.git](https://github.com/username-anda/networksecurity.git)
cd networksecurity

```

### 2. Buat Virtual Environment (Disarankan)

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate

```

### 3. Install Dependensi

Jalankan perintah berikut untuk menginstal kebutuhan proyek:

```bash
pip install -r requirements.txt

```

### 4. Tes Instalasi Paket

Untuk memastikan struktur paket berjalan dengan baik:

```bash
python setup.py install

```

---

## 🛠️ Pengembangan Selanjutnya (To-Do)

* [ ] Implementasi **Data Ingestion** (Pengambilan data trafik jaringan).
* [ ] Implementasi **Data Validation** (Validasi skema data).
* [ ] Pengembangan Model **Machine Learning** untuk deteksi intrusi/anomali.
* [ ] Pembuatan **API Endpoint** untuk integrasi eksternal.

---

<div align="center">
<small>Copyright © 2026 Farhan Kamil Hermansyah (152024150)</small>
</div>

```

```
