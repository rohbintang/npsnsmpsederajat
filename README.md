# Dataset NPSN Nasional

Dataset ini berisi data satuan pendidikan berdasarkan **Nomor Pokok Sekolah Nasional (NPSN)** yang telah dikonversi ke format yang siap digunakan oleh developer.

---

## 📦 Format Data

Dataset tersedia dalam dua format:

* **CSV**
* **JSON**

### CSV

* Encoding: UTF-8
* Delimiter: `;` (semicolon)
* String delimiter: `"`

### JSON

* Format: Array of objects
* Encoding: UTF-8

---

## 🧱 Struktur Data

| Field             | Tipe   | Deskripsi                    |
| ----------------- | ------ | ---------------------------- |
| npsn              | string | Nomor Pokok Sekolah Nasional |
| nama              | string | Nama sekolah                 |
| bentuk_pendidikan | string | Jenjang / jenis pendidikan   |
| alamat_jalan      | string | Alamat lengkap               |
| desa_kelurahan    | string | Desa / Kelurahan             |
| kecamatan         | string | Kecamatan                    |
| kabupaten         | string | Kabupaten / Kota             |
| provinsi          | string | Provinsi                     |
| status_sekolah    | string | Status (NEGERI / SWASTA)     |

---

## ⚙️ Cara Penggunaan

### 1. Import ke Database (contoh Laravel)

* Gunakan CSV sebagai sumber data
* Mapping field sesuai struktur tabel

### 2. Konsumsi JSON

* Bisa langsung digunakan di frontend / API
* Cocok untuk autocomplete, dropdown, dll

---

## 📌 Catatan Penting

* Field menggunakan format **snake_case**
* Tidak ada merge cell atau format Excel kompleks
* Data tidak menjamin update real-time
* Disarankan menggunakan `npsn` sebagai primary key
* CSV menggunakan delimiter `;` untuk menghindari konflik dengan koma pada alamat

---

## 🚀 Rekomendasi Penggunaan

Dataset ini cocok untuk:

* Sistem PPDB / PMB
* Validasi data sekolah
* Dashboard pendidikan
* Integrasi sistem akademik
* Autocomplete pencarian sekolah

---

## 🔄 Versi Dataset

| Versi | Keterangan      |
| ----- | --------------- |
| v1.0  | Initial release |

---

## 📁 Struktur File

```
npsn-dataset/
├── npsn.csv
├── npsn.json
└── README.md
```

---

## ⚠️ Disclaimer

Dataset ini disediakan untuk keperluan pengembangan dan integrasi sistem.
Pengguna bertanggung jawab atas validasi dan penggunaan data sesuai kebutuhan masing-masing.
Tidak ada jaminan bahwa data selalu terbaru atau bebas dari kesalahan.  
Silakan lakukan validasi ulang untuk kebutuhan produksi.

---

## 🤝 Kontribusi

Silakan gunakan, modifikasi, dan kembangkan dataset ini sesuai kebutuhan.

---
