---

```
# Tugas Individu - Setup Computer Vision dengan Anaconda

**Nama:** Tasri Zulfitriyati  
**NIM:** 231001074  
**Kelas:** Informatika C  

---

## 📌 Deskripsi Tugas

Pada tugas individu ini dilakukan proses setup environment Computer Vision menggunakan Anaconda sesuai dengan tutorial yang diberikan.

Proses ini meliputi pencarian package, pengecekan informasi sistem, pembuatan environment baru, serta pengujian library OpenCV.

---

## 🛠 Langkah-Langkah Setup

### 1️⃣ Mencari Package OpenCV

```bash
conda search opencv

Perintah ini digunakan untuk memastikan bahwa package OpenCV tersedia pada repository Anaconda.

2️⃣ Melihat Informasi Anaconda
conda info

Perintah ini menampilkan informasi mengenai versi Anaconda, lokasi instalasi, serta konfigurasi environment.

3️⃣ Membuat Environment Baru
conda create --name TugasML_Tasri python=3.9

Environment baru dibuat untuk memisahkan konfigurasi Python khusus untuk tugas Machine Learning.

4️⃣ Melihat Daftar Environment
conda env list

Perintah ini digunakan untuk memastikan bahwa environment telah berhasil dibuat.

5️⃣ Mengaktifkan Environment
conda activate TugasML_Tasri

Setelah diaktifkan, nama environment akan muncul di awal terminal.

6️⃣ Melihat Daftar Package
conda list

Perintah ini digunakan untuk melihat package yang terinstall pada environment aktif.

7️⃣ Pengujian Library OpenCV

Masuk ke Python:

python

Import library:

import cv2

Cek versi OpenCV:

cv2.__version__

Jika versi OpenCV muncul tanpa error, maka instalasi berhasil.

🧠 Analisis Singkat

Environment Python berhasil dibuat menggunakan Anaconda.

OpenCV berhasil terinstall dan dapat diimport tanpa error.

Versi OpenCV dapat ditampilkan menggunakan cv2.__version__.

Hal ini menunjukkan bahwa konfigurasi Computer Vision telah berhasil disiapkan dan siap digunakan untuk pengembangan lebih lanjut.

✅ Kesimpulan

Setup environment Computer Vision menggunakan Anaconda telah berhasil dilakukan sesuai dengan tutorial.

Environment terpisah telah dibuat, library OpenCV terinstall dengan baik, dan sistem siap digunakan untuk praktik Machine Learning selanjutnya.

🎥 Video Presentasi

Klik di sini untuk menonton video presentasi
