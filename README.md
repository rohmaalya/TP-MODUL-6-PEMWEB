# Tugas Pendahuluan Modul 6 - Pemrograman Web

**Nama:** Rohma Nur Alya

**NIM:** 103092400029

**Topik:** JavaScript dan jQuery  

**Mata Kuliah:** Pemrograman Web (Ganjil 2026/2027)  


---

## Jawaban Pertanyaan Teori

### 1. Jelaskan secara singkat apa itu JavaScript dan kegunaannya! 
**JavaScript** adalah bahasa pemrograman tingkat tinggi yang bersifat *lightweight* dan *interpreted* (dijalankan langsung di browser) yang digunakan untuk membuat halaman web menjadi dinamis dan interaktif.

**Kegunaan JavaScript:**
- Mengubah dan memanipulasi elemen DOM (Document Object Model) secara dinamis.
- Mengelola interaksi pengguna (seperti klik tombol, pergerakan kursor, atau penekanan tombol keyboard).
- Memvalidasi data inputan formulir sebelum dikirimkan ke server.
- Membuat animasi, grafis 2D/3D, dan komunikasi data asynchronous (Ajax/Fetch API).

---

### 2. Jelaskan secara singkat apa itu jQuery dan kegunaannya! 
**jQuery** adalah *library* atau pustaka JavaScript yang bersifat *open-source*, dirancang untuk menyederhanakan penulisan skrip JavaScript pada sisi klien (*client-side*). Selogan utama jQuery adalah *"Write less, do more"*.

**Kegunaan jQuery:**
- Menyederhanakan proses manipulasi elemen HTML/DOM dan manipulasi CSS.
- Mempermudah penanganan *event* (seperti `click`, `hover`, dll.).
- Menyediakan fungsi manipulasi visual dan animasi dasar (seperti `hide()`, `show()`, `animate()`, dll.).
- Mempermudah pengiriman dan penerimaan data dengan server secara *asynchronous* melalui fungsi Ajax.
- Menangani kompatibilitas lintas browser secara otomatis.

---

### 3. Jelaskan perbedaan JavaScript dan jQuery! 

| Karakteristik | JavaScript | jQuery |
| :--- | :--- | :--- |
| **Kategori** | Bahasa Pemrograman murni (*Vanilla JavaScript*). | Pustaka/Library yang dibuat menggunakan JavaScript. |
| **Sintaks Kode** | Cenderung lebih panjang dan kompleks untuk manipulasi DOM. | Lebih ringkas, padat, dan mudah dibaca. |
| **Penggunaan** | Dapat digunakan tanpa dependensi eksternal. | Membutuhkan dependensi file jQuery (CDN atau local file). |
| **Performa** | Eksekusi lebih cepat karena berjalan langsung di browser tanpa perantara. | Sedikit lebih lambat karena harus memproses pustaka jQuery terlebih dahulu. |
| **Sintaks Selektor DOM** | Menggunakan `document.getElementById()`, `document.querySelector()`. | Menggunakan selektor singkat `$('selector')`. |
