# 📊 Finesse: Student Financial Health & Behavior Dashboard

[![Streamlit App] (https://finesse-dashboard.streamlit.app/) [https://finesse-dashboard.streamlit.app/]
Dashboard analitik ini berfungsi sebagai ringkasan eksekutif dan instrumen validasi data untuk mendukung arah pengembangan fitur cerdas pada ekosistem utama aplikasi **Finesse**.

---

## 🎯 Tujuan & Fitur Utama

Dashboard ini dibangun menggunakan Streamlit untuk menyajikan *insight* makro dan mikro bagi pengembangan produk melalui 3 pilar tab analisis utama:
1. **📌 Ringkasan Tren Utama:** Menyajikan dominasi alokasi dana berdasarkan kategori transaksi harian mahasiswa serta karakteristik variabilitas dari setiap metode pembayaran yang digunakan pengguna.
2. **🔍 Detail Distribusi & Karakteristik Data:** Menyajikan sebaran variabilitas nominal uang, sebaran metrik skor kesehatan finansial (*Financial Health Score*), hingga visualisasi tren siklus pengeluaran berkala harian.
3. **💰 Daftar Ekstrim (Top Transaksi):** Fitur deteksi otomatis nilai pencilan (*outliers*) untuk menyaring 10 transaksi tunggal terboros (*masif spend*) dan 10 transaksi terhemat (*micro-transactions*) guna mempermudah audit karakteristik data keuangan.

---

## 🛠️ Teknologi & Pustaka yang Digunakan

Proyek ini dibangun menggunakan ekosistem data science Python modern untuk menjamin performa komputasi yang ringan dan responsif:
* **Streamlit** - Framework utama untuk perancangan antarmuka *user interface* web dashboard interaktif.
* **Pandas** - Manipulasi struktur data, pengolahan *timeseries*, agregasi grup, dan kalkulasi statistik deskriptif.
* **Matplotlib & Seaborn** - Pembuatan visualisasi grafik statistik (barplot, boxplot, histplot, dan lineplot) yang bersih, minimalis, dan informatif.

---

## 📁 Struktur Repositori

Arah penempatan berkas di dalam repositori diatur secara linear agar mempermudah proses automasi server deployment:

```text
📁 Finesse-Dashboard/
│
├── app.py                  # Berkas kode pemrograman utama aplikasi Streamlit
├── finesse_dataset.csv     # Berkas dataset riil perilaku finansial mahasiswa
└── requirements.txt        # Daftar pustaka Python yang wajib diinstal oleh server Cloud

```

---

## 🚀 Langkah Instalasi & Menjalankan di Lokal

Jika Anda ingin menjalankan dashboard analitik ini di lingkungan lokal (*local machine*), ikuti prosedur teknik berikut:

### 1. Kloning Repositori

```bash
git clone(https://github.com/CikitaSembiring/finesse-dashboard.git)(https://github.com/CikitaSembiring/finesse-dashboard.git)
cd finesse-dashboard

```

### 2. Instal Pustaka yang Diperlukan

Pastikan komputer Anda telah terinstal Python. Eksekusi perintah `pip` untuk memasang seluruh dependensi dari file `requirements.txt`:

```bash
pip install -r requirements.txt

```

### 3. Jalankan Aplikasi Streamlit

Jalankan server lokal Streamlit dengan mengeksekusi berkas utama aplikasi:

```bash
streamlit run app.py

```

Aplikasi secara otomatis akan terbuka pada peramban web (*browser*) Anda melalui alamat lokal `http://localhost:8501`.

---

## 💡 Insight & Analisis Perilaku Finansial

Berdasarkan hasil pengolahan data eksploratif (*Exploratory Data Analysis*) riil pada dashboard ini, ditemukan beberapa pola perilaku finansial mahasiswa yang menjadi landasan pengembangan fitur cerdas aplikasi Finesse:

* **Siklus Belanja Tertinggi (Minggu Ke-3):** Rata-rata nominal pengeluaran terbesar per transaksi justru melonjak di minggu ketiga dalam sebulan. Hal ini mencerminkan melemahnya kontrol psikologis belanja mahasiswa setelah kebutuhan pokok awal bulan terpenuhi.
* **Titik Kritis Risiko (Minggu Ke-4):** Kasus penurunan stabilitas finansial (*health score drop*) berulang paling banyak terjadi pada rentang minggu keempat, mengonfirmasi pola krisis likuiditas keuangan mahasiswa akibat fenomena "tanggal tua".

---

## 👥 Tim Pengembang (Finesse Development Team)

Proyek inovasi finansial ini dikembangkan oleh Tim **C26-PSU293** sebagai bagian dari program *Coding Camp powered by DBS Foundation*.

* **Patrick Nicxon Hutabarat** - Full-Stack Web Developer
* **Dame Theresia Rejeki Sidauruk** - Data Science
* **Cikita Natasya Br Sembiring** - Data Scientist 
* **Rayza Indafri Yahya** - AI Engineer
* **Samuel Gautama Manik** - AI Engineer

---

© 2026 Finesse Development Team.

```

```
