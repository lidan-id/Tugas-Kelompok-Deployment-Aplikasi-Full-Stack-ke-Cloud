# 📚 MangaDise – Aplikasi Pembaca Komik Cloud-Native

**MangaDise** adalah aplikasi mobile ringan yang memungkinkan pengguna membaca komik secara daring. Aplikasi ini dibangun dengan **React Native** pada sisi frontend dan **Node.js** di sisi backend, serta menggunakan arsitektur cloud-native dengan layanan dari Google Cloud Platform.

---

## 👥 Daftar Anggota Kelompok

| Nama               | NIM         |
|--------------------|-------------|
| Jeffry Chandra     | 221111220   |
| Jouwine Liepangi   | 221112311   |
| Kevin Lidan        | 221111044   |
| William Tanoto     | 221110870   |

---

## 🌐 URL Aplikasi Live

Silakan akses aplikasi melalui link berikut:  
🔗 [https://expo.dev/accounts/kevinlidan/projects/MangaDise/builds/5633f9b3-a39c-4509-b523-ec6770d611ad](https://expo.dev/accounts/kevinlidan/projects/MangaDise/builds/5633f9b3-a39c-4509-b523-ec6770d611ad)

---

## ☁️ Penjelasan Arsitektur Cloud

Aplikasi ini menggunakan pendekatan full-stack berbasis cloud:

- **Frontend**: Dibangun menggunakan React Native dan dideploy melalui Expo.
- **Backend**: Node.js REST API yang di-deploy ke **Google Cloud Run** dalam bentuk container Docker.
- **Database**: Menggunakan **MongoDB Atlas** sebagai database NoSQL berbasis cloud.
- **Penyimpanan Media**: Gambar komik disimpan di **Google Cloud Storage**.
- **Deployment**: Dilakukan secara manual melalui Google Cloud CLI tanpa pipeline CI/CD.

---

## 📲 Cara Menggunakan Aplikasi

### 1. Registrasi dan Login
- Pengguna yang belum memiliki akun wajib melakukan **registrasi** terlebih dahulu.
- Setelah berhasil registrasi, lanjutkan dengan **login** untuk masuk ke dalam aplikasi.

### 2. Navigasi Utama Aplikasi
Aplikasi MangaDise memiliki **3 tab navigasi utama** yang berada di bagian bawah layar:

#### 🔹 Home (Tengah)
- Menampilkan daftar komik yang tersedia untuk dibaca.
- Klik salah satu komik untuk membuka **halaman detail**, yang berisi:
  - Deskripsi singkat komik.
  - Informasi genre.
  - Tombol untuk **menambahkan ke favorit**.
  - Daftar **chapter** yang bisa dipilih untuk membaca.
- Terdapat fitur **pencarian komik** berdasarkan judul di bagian atas halaman Home.

#### ❤️ Favorite (Kiri)
- Menampilkan komik-komik yang telah ditandai sebagai **favorit** oleh pengguna.
- Komik favorit dapat diakses langsung tanpa perlu mencarinya kembali.

#### 👤 Profile (Kanan)
- Menampilkan informasi akun:
  - **Nama pengguna**.
  - **Foto profil** (dapat diubah).
  - **Jumlah poin** pengguna.
- Tersedia tombol **Logout** untuk keluar dari akun.

---

## 🧪 Cara Menjalankan Proyek di Lokal

### 1. Clone Repository
```bash
git clone <repository_url>
cd MangaDise
