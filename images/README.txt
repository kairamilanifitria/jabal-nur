================================================================================
PANDUAN GAMBAR UNTUK WEBSITE YAYASAN JABAL NUR KEMILING
================================================================================

Folder ini berisi semua gambar yang digunakan di website.
Silakan ganti gambar-gambar placeholder ini dengan foto asli yayasan Anda.

================================================================================
DAFTAR GAMBAR YANG PERLU DISIAPKAN:
================================================================================

1. logo.png
   - Deskripsi: Logo Yayasan Jabal Nur
   - Warna: Hitam/Monochrome (sesuai permintaan)
   - Ukuran Rekomendasi: 500 x 500 px (PNG transparan)
   - Format: PNG (dengan background transparan)
   - Catatan: Logo ini akan muncul di navbar (kiri atas)

2. hero-bg.jpg
   - Deskripsi: Foto background untuk banner utama website
   - Ukuran Rekomendasi: 1920 x 1080 px
   - Format: JPG/JPEG
   - Contoh: Foto gedung panti asuhan, anak-anak bermain, atau pemandangan yayasan
   - Catatan: Foto ini akan ditampilkan dengan overlay warna hijau tosca

3. about.jpg
   - Deskripsi: Foto untuk section "Tentang Kami"
   - Ukuran Rekomendasi: 800 x 600 px
   - Format: JPG/JPEG
   - Contoh: Foto kegiatan panti asuhan, suasana belajar, atau foto bersama anak-anak
   - Catatan: Pastikan foto berkualitas baik dan representatif

4. gallery-1.jpg sampai gallery-6.jpg (MINIMAL 6 FOTO)
   - Deskripsi: Foto-foto kegiatan dan dokumentasi yayasan
   - Ukuran Rekomendasi: 800 x 600 px (landscape) atau 600 x 800 px (portrait)
   - Format: JPG/JPEG
   - Contoh foto yang bisa digunakan:
     * gallery-1.jpg: Kegiatan belajar/sekolah
     * gallery-2.jpg: Kegiatan mengaji/agama
     * gallery-3.jpg: Kegiatan olahraga
     * gallery-4.jpg: Kegiatan seni/kreativitas
     * gallery-5.jpg: Makan bersama/kebersamaan
     * gallery-6.jpg: Kegiatan outdoor/piknik
   
   PENTING! Anda bisa menambah foto galeri lebih dari 6:
   - Tambahkan foto dengan nama: gallery-7.jpg, gallery-8.jpg, dst
   - Edit file index.html di bagian gallery section
   - Copy-paste blok kode gallery-item untuk menambah foto
   - Layout akan otomatis menyesuaikan dan tetap rapih!

================================================================================
TIPS MEMILIH FOTO YANG BAIK:
================================================================================

✅ DO (Lakukan):
- Gunakan foto dengan resolusi tinggi (minimal 800px untuk sisi terpendek)
- Pilih foto yang cerah dan jelas
- Gunakan foto yang menampilkan kegiatan positif dan ceria
- Pastikan tidak ada watermark di foto
- Compress foto agar loading website cepat (gunakan tinyjpg.com)
- Untuk logo, gunakan PNG dengan background transparan

❌ DON'T (Hindari):
- Foto blur atau gelap
- Foto dengan resolusi rendah/pixelated
- Foto yang terlalu berat (>2MB per foto)
- Foto dengan watermark orang lain
- Foto yang melanggar privasi anak-anak (jika ada aturan khusus)

================================================================================
CARA MENGGANTI GAMBAR:
================================================================================

1. Siapkan semua foto yang Anda perlukan
2. Rename foto sesuai dengan nama file di atas (contoh: logo.png, hero-bg.jpg)
3. Paste/copy foto ke folder "images" ini
4. Ganti semua file placeholder yang ada
5. Buka file index.html di browser untuk melihat hasilnya

PENTING: 
- Nama file HARUS SAMA PERSIS (case sensitive)
- Jika nama file berbeda, website tidak akan menampilkan gambar

================================================================================
TOOLS REKOMENDASI UNTUK EDIT FOTO:
================================================================================

1. Untuk compress/resize foto:
   - TinyPNG.com (compress JPG/PNG)
   - Squoosh.app (resize & compress)
   - ILoveIMG.com (berbagai tool edit foto)

2. Untuk edit logo (hapus background):
   - Remove.bg (otomatis hapus background)
   - Photopea.com (alternatif Photoshop gratis online)

3. Untuk crop/resize:
   - Canva.com (mudah untuk pemula)
   - Pixlr.com (editor online gratis)

================================================================================
MENAMBAH FOTO GALERI (LEBIH DARI 6 FOTO):
================================================================================

Jika Anda ingin menambah lebih banyak foto di galeri:

1. Tambahkan foto di folder ini dengan nama:
   gallery-7.jpg, gallery-8.jpg, gallery-9.jpg, dst...

2. Buka file index.html dengan text editor (Notepad++, VS Code, dll)

3. Cari bagian "<!-- Gallery Section -->" 

4. Di dalam <div class="gallery-grid">, Anda akan melihat kode seperti ini:
   
   <div class="gallery-item">
       <img src="images/gallery-1.jpg" alt="Kegiatan Belajar">
       <div class="gallery-overlay">
           <h4>Kegiatan Belajar</h4>
           <p>Suasana belajar yang kondusif</p>
       </div>
   </div>

5. Copy-paste blok kode tersebut

6. Ganti:
   - "gallery-1.jpg" → dengan "gallery-7.jpg" (nomor foto baru)
   - "Kegiatan Belajar" → dengan judul kegiatan di foto
   - "Suasana belajar yang kondusif" → dengan deskripsi singkat

7. Save file dan refresh browser

Layout akan otomatis menyesuaikan jumlah foto tanpa merusak tampilan!

================================================================================
BANTUAN LEBIH LANJUT:
================================================================================

Jika ada kesulitan dalam mengganti gambar atau menambah foto galeri,
silakan hubungi developer atau cari tutorial "cara ganti gambar website HTML"
di YouTube atau Google.

Semoga sukses! 🚀
