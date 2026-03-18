# 🧠 Perintah Dasar Git

Pada materi ini, kamu akan belajar **perintah dasar Git** yang paling sering digunakan.

---

# 📁 1. Membuat Repository

Repository adalah tempat menyimpan project Git.

Gunakan perintah:

```bash
git init
```

👉 Jalankan di dalam folder project

---

## 💡 Contoh:

```bash
mkdir belajar-git
cd belajar-git
git init
```

🎉 Sekarang folder kamu sudah menjadi repository Git

---

# 🔍 2. Melihat Status File

Untuk melihat kondisi file:

```bash
git status
```

---

## 📌 Fungsi:

* Melihat file baru
* Melihat file yang diubah
* Melihat file yang siap di-commit

---

## 💡 Contoh Output:

```text
Untracked files:
  halo.txt
```

👉 Artinya file belum dimasukkan ke Git

---

# ➕ 3. Menambahkan File ke Staging Area

Sebelum disimpan, file harus dimasukkan ke staging area:

```bash
git add .
```

---

## 📌 Penjelasan:

* `.` artinya semua file
* Bisa juga:

```bash
git add nama_file.txt
```

---

# 💾 4. Menyimpan Perubahan (Commit)

Untuk menyimpan perubahan:

```bash
git commit -m "pesan perubahan"
```

---

## 📌 Fungsi:

* Menyimpan perubahan ke dalam Git
* Membuat riwayat (history)

---

## 💡 Contoh:

```bash
git commit -m "menambahkan file halo.txt"
```

---

# 📜 5. Melihat Riwayat Perubahan

Untuk melihat semua commit:

```bash
git log
```

---

## 📌 Informasi yang ditampilkan:

* ID commit
* Nama pembuat
* Waktu
* Pesan commit

---

## 💡 Versi Singkat:

```bash
git log --oneline
```

---

# 🔄 Alur Dasar Git

Berikut alur kerja Git yang harus kamu ingat:

```text
Edit file → git add → git commit
```

---

## 🧠 Penjelasan:

1. Edit file
2. Tambahkan ke staging (`git add`)
3. Simpan perubahan (`git commit`)

👉 Ulangi proses ini setiap ada perubahan

---

# 🚀 Contoh Alur Lengkap

```bash
# cek status
git status

# tambah file
git add .

# simpan perubahan
git commit -m "update file latihan"

# lihat riwayat
git log --oneline
```

---

# ⚠️ Kesalahan yang Sering Terjadi

## ❌ Lupa git add

👉 File tidak ikut ke commit

## ❌ Pesan commit tidak jelas

```bash
git commit -m "update"
```

---

# 💡 Tips Profesional

Gunakan pesan commit yang jelas:

❌ Kurang baik:

```bash
git commit -m "update"
```

✅ Lebih baik:

```bash
git commit -m "menambahkan fitur login siswa"
```

---

# 🔥 Kesimpulan

Perintah utama Git:

* `git init` → membuat repository
* `git status` → melihat status
* `git add` → menyiapkan file
* `git commit` → menyimpan perubahan
* `git log` → melihat riwayat

---

💻 Selamat! Kamu sudah memahami dasar Git 🚀
