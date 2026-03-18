# ⚙️ Install Git

Pada materi ini, kita akan belajar cara **menginstall Git** dan memastikan Git siap digunakan.

---

# 💻 Install Git di Windows

## 🔽 1. Download Git

Download Git dari website resmi:
👉 https://git-scm.com

Klik tombol:
👉 **Download for Windows**

---

## 📦 2. Install Git

* Buka file installer yang sudah didownload
* Klik **Next** terus sampai selesai
* Tidak perlu mengubah pengaturan (default saja)

💡 Untuk pemula: cukup klik **Next → Next → Next → Install**

---

# ✅ 3. Cek Apakah Git Berhasil Terinstall

Buka:

* CMD / Command Prompt
  atau
* Terminal / PowerShell

Lalu ketik:

```bash
git --version
```

---

## 🎉 Jika Berhasil

Akan muncul seperti ini:

```bash
git version 2.xx.x
```

👉 Artinya Git sudah siap digunakan

---

## ❌ Jika Gagal

Jika muncul:

```text
git is not recognized
```

👉 Artinya:

* Git belum terinstall dengan benar
* Atau belum terdeteksi di sistem

💡 Solusi:

* Restart komputer
* Install ulang Git

---

# 🔧 Konfigurasi Awal (WAJIB)

Setelah install, kamu harus mengatur identitas Git.

---

## 👤 1. Set Username

```bash
git config --global user.name "Nama Kamu"
```

---

## 📧 2. Set Email

```bash
git config --global user.email "email@gmail.com"
```

---

## 💡 Contoh

```bash
git config --global user.name "Bagus"
git config --global user.email "bagus@gmail.com"
```

---

# 🔍 3. Cek Konfigurasi

Untuk memastikan berhasil, jalankan:

```bash
git config --list
```

---

## 🎉 Jika Berhasil

Akan muncul:

```text
user.name=Bagus
user.email=bagus@gmail.com
```

---

# 📌 Kenapa Ini Penting?

Setiap kamu melakukan commit, Git akan mencatat:

* Siapa yang membuat perubahan
* Kapan perubahan dilakukan

---

## 🧠 Analogi

> Seperti menulis nama di buku tugas
> agar guru tahu siapa yang mengerjakan

---

# ⚠️ Catatan Penting

* Gunakan email yang sama dengan akun GitHub
* Jangan salah ketik username
* Konfigurasi ini cukup dilakukan **sekali saja**

---

# 🚀 Ringkasan

Langkah install Git:

1. Download Git
2. Install Git
3. Cek dengan `git --version`
4. Set username & email

---

💻 Git siap digunakan! Lanjut ke materi berikutnya 🚀
