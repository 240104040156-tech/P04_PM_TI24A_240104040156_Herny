# README - WargaHubP04

## 🎓 Identitas Praktikum
- **Nama:** Herny
- **NIM:** 240104040156
- **Kelas:** TI24A 
- **Perangkat Pengujian:** Laptop Windows 11 & Emulator Android Studio (Medium Phone API 34)
- **Versi Alat:** Android Studio Jellyfish / Ladybug, Kotlin 1.9+, AGP 8.x, Gradle 8.x

---

## 🚀 Cara Membuka dan Run Proyek
1. Buka aplikasi **Android Studio**.
2. Pilih menu **File > Open**, lalu arahkan ke folder proyek `WargaHubP04`.
3. Tunggu proses **Gradle Sync** selesai.
4. Pilih emulator **Medium Phone API 34** pada toolbar bagian atas.
5. Klik tombol **Run 'app'** (ikon segitiga hijau `▶`) atau tekan `Shift + F10`.

---

## 📱 Ringkasan Fitur Aplikasi
1. **Beranda (HomeFragment):** Halaman pembuka yang berisi deskripsi pengantar aplikasi dan tombol navigasi `Lihat Daftar Laporan`.
2. **Daftar Laporan (ListFragment):** Menampilkan 15 item laporan lingkungan menggunakan `RecyclerView` dan `ListAdapter`.
3. **Rincian Laporan (DetailFragment):** Menampilkan rincian data laporan secara spesifik berdasarkan argumen `laporan_id` yang dikirim via Safe Args.
4. **Simulasi Mode Kosong:** Menampilkan visualisasi data 0 (*Empty State*) beserta tombol pemulihannya.
5. **Penanganan Error (Safe State):** Menampilkan pesan Toast visual aman saat memilih ID invalid tanpa menyebabkan *app crash*.

---

## ⚠️ Batas Data Contoh (Simulasi)
> **Catatan:** Seluruh data laporan yang ditampilkan di dalam aplikasi ini (Zona 1 hingga Zona 15) **hanya bersifat data contoh simulasi lokal** untuk keperluan praktikum navigasi UI/UX dan **belum terhubung ke database server/backend nyata**.