<div align="center">

<img width="720" height="1600" alt="Preview Tampilan Termux" src="https://github.com/user-attachments/assets/f4c1af4c-cf85-4eed-a48b-63679b83c6ec" />

# 🚀 Tampilan Termux Premium

**Tampilan Termux biar makin fresh, elegan, neon, dan gak ngebosenin.**  
Sekali install, tampilannya bisa otomatis muncul setiap buka Termux.

---

[![Developer](https://img.shields.io/badge/Developer-ALIZZ-FF00FF?style=for-the-badge&logo=github)](https://github.com/ALIZZ151)
[![Tools](https://img.shields.io/badge/Tools-Tampilan%20Termux-00AAFF?style=for-the-badge)](https://github.com/ALIZZ151/tampilan)
[![Version](https://img.shields.io/badge/Version-2.0%20Premium-FFCC00?style=for-the-badge)](https://github.com/ALIZZ151/tampilan)
[![Termux](https://img.shields.io/badge/Support-Termux-00FF88?style=for-the-badge&logo=android)](https://termux.dev/)

</div>

---

## ✨ Tentang Tools Ini

Tools ini dibuat buat kamu yang pengen tampilan Termux jadi lebih keren dan beda dari yang lain.

Bukan cuma tampilan biasa, tapi dibuat dengan gaya **Cyberpunk Neon** yang mencolok, clean, dan enak dilihat.

Cocok buat:

- Biar Termux gak polos
- Biar tampilan terminal lebih aesthetic
- Biar keliatan lebih premium
- Biar makin semangat ngoding di Termux
- Biar tampilan muncul otomatis setiap buka Termux

---

## 🎨 Preview Tampilan

<div align="center">

<img width="720" height="1012" alt="Preview 1" src="https://github.com/user-attachments/assets/c2e6e199-dc28-43f6-807b-3a61513a7422" />

<br><br>

<img width="720" height="1012" alt="Preview 2" src="https://github.com/user-attachments/assets/d83ed72e-ec6f-41ca-accf-11cb815baa52" />

<br><br>

<img width="720" height="1012" alt="Preview 3" src="https://github.com/user-attachments/assets/6e078930-bb6e-4c02-ae4a-d9e5c7583c45" />

</div>

---

## 🔥 Fitur

- Tampilan Termux lebih modern
- Gaya warna neon cyberpunk
- Logo terminal lebih mencolok
- Info sistem lebih rapi
- Ada nama developer
- Ringan dan mudah dipasang
- Cocok buat pemula
- Bisa langsung jalan di Termux
- Bisa otomatis muncul setiap buka Termux

---

## 📦 Bahan Yang Dibutuhkan

Sebelum install, pastikan kamu sudah punya aplikasi **Termux**.

Kalau belum punya, install dulu Termux versi terbaru.

---

## 📥 Cara Install Di Termux

Salin command di bawah ini satu per satu ke Termux.

```bash
pkg update && pkg upgrade -y
```

```bash
pkg install git bash -y
```

```bash
git clone https://github.com/ALIZZ151/tampilan.git
```

```bash
cd tampilan
```

```bash
chmod +x tampilan.sh
```

```bash
bash tampilan.sh
```

---

## ✅ Biar Tampilan Muncul Terus Saat Buka Termux

Kalau tampilannya hilang setelah Termux ditutup lalu dibuka lagi, itu normal.

Berarti script cuma dijalankan manual, belum dipasang ke startup Termux.

Supaya tampilan otomatis muncul setiap buka Termux, jalankan command ini:

```bash
echo 'bash "$HOME/tampilan/tampilan.sh"' >> ~/.bashrc
```

Setelah itu tutup Termux, lalu buka lagi.

Kalau berhasil, tampilan akan muncul otomatis setiap masuk Termux.

---

## ⚡ Cara Install Cepat Permanen

Kalau gak mau ribet, langsung copy command ini ke Termux:

```bash
pkg update && pkg upgrade -y && pkg install git bash -y && rm -rf ~/tampilan && git clone https://github.com/ALIZZ151/tampilan.git ~/tampilan && cd ~/tampilan && chmod +x tampilan.sh && bash tampilan.sh && (grep -qxF 'bash "$HOME/tampilan/tampilan.sh"' ~/.bashrc || echo 'bash "$HOME/tampilan/tampilan.sh"' >> ~/.bashrc)
```

Setelah command selesai, tutup Termux lalu buka lagi.

Tampilan akan otomatis muncul setiap masuk Termux.

---

## 🔁 Cara Menjalankan Ulang Manual

Kalau mau menjalankan manual:

```bash
cd ~/tampilan
bash tampilan.sh
```

---

## 🛠️ Kalau Error

### 1. Command `git` tidak ditemukan

Jalankan:

```bash
pkg install git -y
```

### 2. File tidak bisa dijalankan

Jalankan:

```bash
cd ~/tampilan
chmod +x tampilan.sh
bash tampilan.sh
```

### 3. Tampilan hilang pas buka Termux lagi

Jalankan:

```bash
echo 'bash "$HOME/tampilan/tampilan.sh"' >> ~/.bashrc
```

Lalu tutup Termux dan buka lagi.

### 4. Folder sudah ada

Kalau muncul error folder sudah ada, hapus dulu folder lama:

```bash
rm -rf ~/tampilan
```

Lalu clone ulang:

```bash
git clone https://github.com/ALIZZ151/tampilan.git ~/tampilan
cd ~/tampilan
bash tampilan.sh
```

---

## 🧹 Cara Menghapus Tampilan Otomatis

Kalau suatu saat mau balikin Termux seperti semula, buka file `.bashrc`:

```bash
nano ~/.bashrc
```

Hapus baris ini:

```bash
bash "$HOME/tampilan/tampilan.sh"
```

Lalu simpan:

```txt
CTRL + X
Y
ENTER
```

Tutup Termux, lalu buka lagi.

---

## ⚠️ Catatan Penting

Pastikan folder repo tetap ada di home Termux:

```bash
~/tampilan
```

Kalau folder `tampilan` dihapus, tampilan otomatis tidak akan jalan.

Kalau nama file script kamu bukan `tampilan.sh`, cek dulu isi foldernya:

```bash
ls ~/tampilan
```

Lalu jalankan sesuai nama file script kamu.

Contoh:

```bash
bash nama-file.sh
```

---

## 👑 Developer

Tools ini dibuat oleh:

```txt
ALIZZ
```

GitHub:

```txt
https://github.com/ALIZZ151
```

---

## 🤝 Support

Kalau tools ini bermanfaat, jangan lupa kasih star repo ini biar makin semangat update versi berikutnya.

<div align="center">

### ⭐ Jangan lupa star repo ini ⭐

**Dibuat dengan niat, bukan sekadar script biasa.**

</div><img width="720" height="1028" alt="1001279684" src="https://github.com/user-attachments/assets/c8ae5116-991b-460c-9790-8a50f47ae1ba" />
