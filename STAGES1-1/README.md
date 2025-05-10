# Studi Kasus: Belajar Python untuk Eco-Techno Leader dengan Pendekatan Customer-Centric

Selamat datang di studi kasus sederhana ini! Studi kasus ini dirancang untuk pemula yang ingin mengenal Python tanpa perlu menginstal library tambahan. Kita akan membuat program kecil bertema Eco-Techno Leader yang berfokus pada pendekatan Customer-Centric Approach, yaitu memprioritaskan kebutuhan pelanggan untuk membangun loyalitas. Program ini akan membantu Anda memahami dasar-dasar Python seperti mencetak pesan, menggunakan variabel, melakukan perhitungan sederhana, dan meminta input dari pengguna.

**Tema:** Anda adalah seorang Eco-Techno Leader yang sedang merancang solusi energi ramah lingkungan untuk pelanggan, seperti panel surya untuk rumah. Anda ingin memahami kebutuhan pelanggan dan memberikan solusi yang sesuai untuk meningkatkan kepuasan mereka.

---

## Tujuan

* Mengenal perintah dasar Python (`print()`, variabel, `input()`, dan operasi matematika).
* Membuat program sederhana yang mencerminkan pendekatan customer-centric.
* Menginspirasi pemula untuk berpikir tentang teknologi hijau.

---

## Prasyarat

* Anda hanya perlu menginstal Python (versi 3.x) di komputer Anda. Unduh dari [python.org](https://www.python.org/downloads/) jika belum terinstal.
* Gunakan editor teks sederhana seperti Notepad, atau gunakan Visual Studio Code untuk pengalaman yang lebih baik.
* Tidak perlu menginstal library tambahan seperti `pip`.

---

## Studi Kasus: Kalkulator Kebutuhan Energi Rumah Pelanggan

### Latar Belakang
Sebagai Eco-Techno Leader, Anda bekerja untuk perusahaan energi ramah lingkungan bernama "GreenHome Solutions". Tugas Anda adalah membantu pelanggan memahami kebutuhan energi mereka untuk menggunakan panel surya. Anda akan membuat program Python sederhana yang:

* Menyapa pelanggan dengan ramah.
* Meminta input jumlah perangkat listrik di rumah mereka.
* Menghitung estimasi kebutuhan energi harian berdasarkan input pelanggan.
* Memberikan saran sederhana untuk solusi ramah lingkungan.

Pendekatan customer-centric di sini adalah memastikan pelanggan merasa didengar dengan meminta input mereka dan memberikan solusi yang relevan berdasarkan kebutuhan mereka.

---

## Cara Menjalankan

1.  **Buat File Python:**
    Buat file bernama `greenhome.py`. Anda bisa menggunakan perintah berikut di terminal/bash untuk membuat file dan langsung menyalin seluruh kode program ke dalamnya:

    ```bash
    cat << EOF > greenhome.py
    print("Selamat datang di GreenHome Solutions!")
    print("Kami akan membantu Anda menemukan solusi energi ramah lingkungan.")

    # Meminta input dari pelanggan
    jumlah_perangkat = int(input("Masukkan jumlah perangkat listrik di rumah Anda: "))
    print("Jumlah perangkat listrik Anda:", jumlah_perangkat)

    # Menghitung kebutuhan energi
    energi_per_perangkat = 0.5  # kWh per hari
    total_energi = jumlah_perangkat * energi_per_perangkat
    print("Kebutuhan energi harian Anda:", total_energi, "kWh")

    # Memberikan saran
    print("Saran: Gunakan panel surya untuk memenuhi kebutuhan energi Anda dan hemat biaya!")
    print("Terima kasih telah memilih solusi ramah lingkungan bersama GreenHome Solutions!")
    EOF
    ```
    Salin dan tempel seluruh blok kode di atas (termasuk `cat << EOF > greenhome.py` dan `EOF` di akhir) ke terminal Anda, lalu tekan Enter.

2.  **Jalankan Program:**
    Setelah file `greenhome.py` dibuat dan berisi kode, jalankan dengan perintah:

    ```bash
    python greenhome.py
    ```
    Atau jika Anda menggunakan Python 3 secara spesifik:
    ```bash
    python3 greenhome.py
    ```

---

## Langkah-langkah Pembuatan Program (Detail)

### Langkah 1: Menyapa Pelanggan

Kode awal untuk menyapa pelanggan:
```python
print("Selamat datang di GreenHome Solutions!")
print("Kami akan membantu Anda menemukan solusi energi ramah lingkungan.")

---
Penjelasan:

print() digunakan untuk menampilkan teks di layar.
Pesan ini mencerminkan pendekatan customer-centric dengan nada ramah dan mengundang.

Output saat Anda menjalankan kode (python greenhome.py):
Selamat datang di GreenHome Solutions!
Kami akan membantu Anda menemukan solusi energi ramah lingkungan.
---

### Langkah 2: Meminta Input dari Pelanggan
#### Sekarang, kita akan meminta pelanggan memasukkan jumlah perangkat listrik di rumah mereka. Tambahkan kode berikut ke greenhome.py:
print("Selamat datang di GreenHome Solutions!")
print("Kami akan membantu Anda menemukan solusi energi ramah lingkungan.")
---
### Meminta input dari pelanggan
jumlah_perangkat = int(input("Masukkan jumlah perangkat listrik di rumah Anda: "))
print("Jumlah perangkat listrik Anda:", jumlah_perangkat)
---
Penjelasan:

input() meminta pelanggan mengetik sesuatu di layar, dan hasilnya disimpan sebagai teks (string).
int() mengubah teks menjadi angka agar bisa digunakan untuk perhitungan.
jumlah_perangkat adalah variabel yang menyimpan input pelanggan.
Baris terakhir mencetak input pelanggan untuk memastikan mereka merasa didengar (customer-centric).

Output (misalnya, pelanggan memasukkan 5):
Selamat datang di GreenHome Solutions!
Kami akan membantu Anda menemukan solusi energi ramah lingkungan.
Masukkan jumlah perangkat listrik di rumah Anda: 5
Jumlah perangkat listrik Anda: 5
---

### Langkah 3: Menghitung Kebutuhan Energi
#### Untuk membuatnya sederhana, anggap saja setiap perangkat listrik rata-rata membutuhkan 0.5 kWh energi per hari. Kita akan menghitung total kebutuhan energi harian. Perbarui kode menjadi:

print("Selamat datang di GreenHome Solutions!")
print("Kami akan membantu Anda menemukan solusi energi ramah lingkungan.")
---
### Meminta input dari pelanggan

jumlah_perangkat = int(input("Masukkan jumlah perangkat listrik di rumah Anda: "))
print("Jumlah perangkat listrik Anda:", jumlah_perangkat)
---
#### Menghitung kebutuhan energi
energi_per_perangkat = 0.5  # kWh per hari
total_energi = jumlah_perangkat * energi_per_perangkat
print("Kebutuhan energi harian Anda:", total_energi, "kWh")
---
Penjelasan:

energi_per_perangkat adalah variabel yang menyimpan nilai tetap (0.5 kWh).
total_energi dihitung dengan mengalikan jumlah_perangkat dengan energi_per_perangkat.
Hasilnya ditampilkan dengan print() untuk memberi pelanggan informasi yang relevan.

Output (misalnya, pelanggan memasukkan 5):
Selamat datang di GreenHome Solutions!
Kami akan membantu Anda menemukan solusi energi ramah lingkungan.
Masukkan jumlah perangkat listrik di rumah Anda: 5
Jumlah perangkat listrik Anda: 5
Kebutuhan energi harian Anda: 2.5 kWh
---
### Langkah 4: Memberikan Saran Ramah Lingkungan
#### Terakhir, kita akan memberikan saran sederhana untuk pelanggan agar mereka merasa mendapatkan solusi yang bermanfaat. Perbarui kode menjadi:
print("Selamat datang di GreenHome Solutions!")
print("Kami akan membantu Anda menemukan solusi energi ramah lingkungan.")
---
# Meminta input dari pelanggan
jumlah_perangkat = int(input("Masukkan jumlah perangkat listrik di rumah Anda: "))
print("Jumlah perangkat listrik Anda:", jumlah_perangkat)
---
# Menghitung kebutuhan energi
energi_per_perangkat = 0.5  # kWh per hari
total_energi = jumlah_perangkat * energi_per_perangkat
print("Kebutuhan energi harian Anda:", total_energi, "kWh")
---
# Memberikan saran
print("Saran: Gunakan panel surya untuk memenuhi kebutuhan energi Anda dan hemat biaya!")
print("Terima kasih telah memilih solusi ramah lingkungan bersama GreenHome Solutions!")
---
Penjelasan:

Baris terakhir menambahkan saran yang relevan dengan tema Eco-Techno Leader.
Pesan terima kasih memperkuat pendekatan customer-centric dengan menunjukkan apresiasi.

Output (misalnya, pelanggan memasukkan 5):
Selamat datang di GreenHome Solutions!
Kami akan membantu Anda menemukan solusi energi ramah lingkungan.
Masukkan jumlah perangkat listrik di rumah Anda: 5
Jumlah perangkat listrik Anda: 5
Kebutuhan energi harian Anda: 2.5 kWh
Saran: Gunakan panel surya untuk memenuhi kebutuhan energi Anda dan hemat biaya!
Terima kasih telah memilih solusi ramah lingkungan bersama GreenHome Solutions!
---
Langkah Selanjutnya
Selamat! Anda telah membuat program Python sederhana yang:

Menyapa pelanggan dengan ramah.
Meminta input kebutuhan mereka.
Memberikan solusi berdasarkan input.
Menggunakan pendekatan customer-centric untuk membangun loyalitas.

Tantangan untuk Anda:

Coba ubah pesan selamat datang menjadi lebih personal, misalnya meminta nama pelanggan dengan input() dan mencetak "Halo, [nama]!".
Ubah nilai energi_per_perangkat menjadi 0.3 kWh dan lihat bagaimana hasilnya berubah.
Tambahkan pesan lain di saran, seperti "Matikan perangkat saat tidak digunakan untuk hemat energi!"

Teruslah berlatih dengan Python, dan jadilah Eco-Techno Leader yang menciptakan solusi ramah lingkungan untuk dunia yang lebih baik!
---
