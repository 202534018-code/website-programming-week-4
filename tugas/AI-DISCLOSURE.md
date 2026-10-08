# AI Disclosure — Website Programming

## Minggu 3 (Tugas 3)
- **Tool:** Gemini
- **Prompt Utama:** "Bantu buatkan CSS eksternal bersistem token visual dengan custom properties, box-sizing, typography unit relatif, dan accessible keyboard focus."
- **Saran AI yang Digunakan:** Pembuatan variabel CSS (`:root`), pengaturan `focus-visible` untuk aksesibilitas keyboard, dan pembatasan panjang teks dengan unit `ch`.
- **Pengujian & Perubahan Mandiri:** 
  - Menguji kontras warna tombol dan teks utama agar memenuhi rasio WCAG.
  - Memastikan file style.css terhubung tepat ke file index.html.

---

## Minggu 4 (Tugas 4)
- **Tool:** Gemini
- **Prompt Utama:**
  1. "Bantu buatkan struktur Flexbox untuk main-aside dan daftar card sesuai modul Tugas 4."
  2. "Bantu atur CSS agar gambar dan teks tidak mengalami horizontal overflow pada layar 320px."
- **Saran AI yang Digunakan:**
  - Penggunaan `display: flex`, `flex-wrap: wrap`, dan `gap` pada container utama.
  - Penggunaan `min-width: 0` pada flex item dan `max-width: 100%` pada gambar.
  - Penggunaan `position: relative` pada card dan `position: absolute` pada badge.
- **Pengujian & Perubahan Mandiri:**
  - Menyesuaikan ukuran foto profil dan gambar galeri agar tidak kebesaran.
  - Menguji alur fokus tombol Tab keyboard agar sesuai dengan urutan baca visual.
  - Memeriksa tampilan layout pada viewport 320px dan zoom 200% menggunakan Chrome DevTools.
- **Catatan Masalah Overflow & Perbaikan:**
  - **Masalah:** Gambar atau teks yang terlalu panjang dapat menyebabkan horizontal scroll pada layar sempit (320px).
  - **Solusi:** Menambahkan `max-width: 100%` pada elemen gambar dan `overflow-wrap: anywhere` pada elemen teks dan link.