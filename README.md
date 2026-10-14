# SQL Student Registration

**Hands-On 1 — Student Registration SQL Server**
---
| Keterangan | Detail |
|:---|:---|
| **Nama** | Hidayah Nur Septiani |
| **NRP** | 5025241247 |
| **Kelas** | PBKK C |

---

## Tujuan Praktikum

Praktikum ini bertujuan agar mahasiswa mampu:

- Menyiapkan dan menghubungkan SQL Server pada komputer pribadi.
- Membuat database StudentRegistrationDB.
- Membuat tabel Programs dan Students.
- Menerapkan relasi One-to-Many (1:N) antartabel.
- Memasukkan dan menampilkan data menggunakan SQL Query.
- Menguji relasi data menggunakan INNER JOIN.
- Menghubungkan database dengan aplikasi desktop menggunakan C# dan WPF.

---

## Hasil Praktikum

### 1. Koneksi ke SQL Server

![Koneksi ke SQL Server](https://github.com/user-attachments/assets/8ab4857b-2b3d-44b2-9cdc-20f078d84c48)

SQL Server berhasil dihubungkan melalui SSMS menggunakan instance `.\SQLEXPRESS`. Koneksi ini digunakan untuk mengelola database dan menjalankan perintah SQL.

### 2. Pembuatan Database `StudentRegistrationDB`

![Database StudentRegistrationDB](https://github.com/user-attachments/assets/616748c8-d2f0-41aa-86d8-3416195a5f71)

Database `StudentRegistrationDB` berhasil dibuat sebagai tempat penyimpanan data program studi dan mahasiswa.

### 3. Tabel `Programs`

![Tabel Programs](https://github.com/user-attachments/assets/5405663e-1cad-498c-877c-9aa442bf13b6)

Tabel `Programs` digunakan untuk menyimpan informasi program studi. Data ditampilkan menggunakan query SELECT * FROM Programs;

### 4. Tabel `Students`

![Tabel Students](https://github.com/user-attachments/assets/d4f86ef8-d329-41f3-942e-b7027facdd3a)

Tabel `Students` digunakan untuk menyimpan informasi mahasiswa. Pengujian dilakukan menggunakan query SELECT * FROM Students;

### 5. Pengujian Relasi Menggunakan `INNER JOIN`

![Hasil INNER JOIN](https://github.com/user-attachments/assets/f39974db-4a5c-4586-813c-a0e1033f141c)

Relasi antara tabel `Programs` dan `Students` diuji menggunakan `INNER JOIN` untuk menggabungkan data mahasiswa dengan program studi yang terkait.

### 6. Implementasi Aplikasi WPF

![Aplikasi WPF Student Registration](https://github.com/user-attachments/assets/eb2e9b11-7881-45ed-bbbf-a7cef48d2208)

Aplikasi desktop berbasis **C# dan WPF** digunakan untuk menampilkan data mahasiswa yang tersimpan di database `StudentRegistrationDB`.

Fitur utama aplikasi:

- **Refresh Data** — Memuat ulang data mahasiswa dari database.
- **Total Mahasiswa** — Menampilkan jumlah mahasiswa yang tercatat.
- **Tabel Mahasiswa** — Menampilkan data mahasiswa dalam bentuk tabel.

---
