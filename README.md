# 🛒 IKHWAN STORE - Premium Men's Streetwear & Casual Outfit
> **Business Overview & Technical Documentation Prototype V1.0 (2026)**

Dokumen ini berisi gambaran umum bisnis (*Business Overview*), strategi pemasaran, manajemen produk, hingga arsitektur sistem dari prototipe *e-commerce* **IKHWAN STORE**. Dokumen ini dirancang siap pakai untuk keperluan presentasi bisnis, dokumentasi proyek kuliah, maupun panduan pengembangan sistem lebih lanjut.

---

## 1. Profil Bisnis & Value Proposition

### 🏢 Nama Bisnis
**IKHWAN STORE** (Dioperasikan di bawah entitas korporasi purwarupa: *Ikhwan Store Prototype Corp.*)

### 📝 Deskripsi Bisnis
IKHWAN STORE adalah platform *e-commerce* spesialis pakaian pria premium yang mengusung konsep perpaduan antara *modern oversized streetwear* dan *Japanese urban style*. Kami hadir untuk memenuhi kebutuhan sandang pria modern yang menginginkan tampilan kasual, estetik, namun tetap rapi (*smart-casual*) melalui pengalaman belanja digital yang minimalis dan responsif.

### 💡 Value Proposition (Nilai Jual Unik)
* **Curated Japanese Urban Silhouette:** Menyediakan potongan pakaian khas jalanan Jepang (*drop shoulder*, *oversized*, *minimalist cut*) yang sulit ditemukan di ritel konvensional dengan harga terjangkau.
* **Heavyweight & Premium Durability:** Fokus pada material kain berkualitas tinggi dan tebal (seperti *Cotton Combed 24s Heavyweight*, *Semi-Wool Premium*, dan *Micro-Corduroy*).
* **Hyper-Local Convenience:** Memberikan penawaran gratis ongkos kirim tanpa syarat untuk wilayah operasional Bandung Raya.

---

## 2. Target Pasar & Segmentasi Pelanggan

IKHWAN STORE membidik pasar pria dengan segmentasi yang sangat spesifik untuk memastikan efektivitas konversi penjualan:

* **Segmentasi Demografis:** * Pria, usia 18–30 tahun (Generasi Z dan Milenial Muda).
    * Status: Mahasiswa, *first-jobber*, dan profesional muda di bidang industri kreatif/teknologi.
    * Pendapatan: Menengah hingga menengah ke atas (SES B & A).
* **Segmentasi Geografis:** Urban dan sub-urban, dengan fokus utama logistik awal di wilayah **Bandung Raya** dan ekspansi nasional ke kota-kota besar di Indonesia.
* **Segmentasi Psikografis:** * Pria yang memiliki ketertarikan tinggi terhadap estetika visual, sinematografi, tren kultur pop Jepang, dan fesyen kasual modern.
    * Aktif menggunakan media sosial tren visual seperti TikTok, Instagram, dan YouTube.
    * Menyukai pakaian longgar (*oversized*) untuk kenyamanan bergerak sekaligus menjaga penampilan tetap modis.

---

## 3. Analisis Pasar Singkat & Kompetitor

### 📈 Tren Pasar
Pasar fesyen pria, khususnya kategori *streetwear* lokal, mengalami lonjakan permintaan yang masif dalam beberapa tahun terakhir. Konsumen pria kini jauh lebih peduli terhadap *cutting* (potongan pakaian) dan kualitas bahan dibandingkan sekadar logo *brand*. Tren *oversized apparel* yang diadopsi dari kultur Harajuku dan Seoul kini telah menjadi standar pakaian harian (*dailywear*) anak muda di Indonesia.

### ⚔️ Lanskap Kompetitor
* **Kompetitor Langsung:** *Brand-brand* lokal fesyen pria yang bermain di ranah *streetwear* dasar (seperti Erigo, Roughneck 1991, atau Wadezig).
* **Keunggulan Kompetitif IKHWAN STORE:** Kompetitor mayoritas berfokus pada desain grafis sablon yang mencolok (*graphic t-shirt*), sedangkan IKHWAN STORE mengambil ceruk pasar **Minimalis Kosong (*Plain Minimalist*)** dengan fokus keunggulan pada kekuatan tekstur bahan kain (Korduroi, Linen, Rajut) serta fleksibilitas padu padan (*layering outfit*).

---

## 4. Strategi Manajemen Produk & Katalog

Katalog produk dikelola secara digital melalui struktur data terstruktur yang diklasifikasikan ke dalam kategori taktis demi kemudahan navigasi pengguna (*User Experience*):

### A. Klasifikasi Kategori
1.  **Atasan (T-Shirt & Kemeja):** Fokus pada kenyamanan harian, sirkulasi udara optimal, dan potongan longgar.
2.  **Outerwear (Blazer & Jaket):** Fokus pada struktur siluet tubuh yang gagah, kehangatan, dan kebutuhan gaya formal-santai.

### B. Struktur Visual & Informasi Katalog (Data Eksisting)

| ID | Nama Produk | Kategori | Harga | Visual Ekspektasi (Unsplash Verified) |
|---|---|---|---|---|
| 1 | Oversized Heavyweight T-Shirt Black | Atasan | Rp 149.000 | Kaos hitam polos tebal, *drop shoulder style* |
| 2 | Japanese Street Oversized Blazer Grey | Outerwear | Rp 389.000 | Blazer abu-abu longgar khas Harajuku |
| 3 | Kemeja Flanel Kasual Kotak-Kotak | Atasan | Rp 195.000 | Flanel motif kotak gelap maskulin |
| 4 | Casual Structured Tech Blazer Black | Outerwear | Rp 420.000 | Blazer hitam formal dari kain *anti-wrinkle* |
| 5 | Kemeja Linen Kerah Shanghai White | Atasan | Rp 175.000 | Kemeja putih kerah sanghai, kain linen berongga |
| 6 | Oversized Denim Worker Jacket Blue | Outerwear | Rp 345.000 | Jaket denim biru *pre-washed* dengan saku kargo |
| 7 | Premium Soft-Knit Knitwear Sweater | Atasan | Rp 225.000 | Sweater rajut estetik benang akrilik lembut |
| 8 | Minimalist Corduroy Overshirt Jacket | Atasan | Rp 189.000 | Kemeja luar (*overshirt*) berbahan korduroi |

Setiap produk dilengkapi dengan fitur **Modal Detail Popup** yang menyajikan deskripsi naratif emosional untuk meningkatkan hasrat pembelian (*impulse buying*) serta sistem *rating* bintang transparan untuk membangun kepercayaan instan (*social proof*).

---

## 5. Model Bisnis & Revenue Stream

IKHWAN STORE beroperasi menggunakan model bisnis **Direct-to-Consumer (D2C) E-Commerce Retailing**. Kami memotong rantai distribusi konvensional dengan memproduksi/mengurasi pakaian langsung dan menjualnya secara mandiri via platform digital resmi.

### 💰 Revenue Stream (Arus Pendapatan)
1.  **Penjualan Produk Utama:** Pendapatan utama dari margin keuntungan bersih penjualan pakaian (Atasan & Outerwear) berkisar antara 40% - 50% dari Harga Pokok Penjualan (HPP).
2.  **Koleksi Bundling Premium:** Penjualan paket kombo (misal: Paket *Top-to-Bottom Layering* berisi Kaos Oversized + Blazer) dengan nilai transaksi rata-rata (*Average Order Value*) yang lebih tinggi.

---

## 6. Strategi Harga, Promosi, dan Diskon

### 💵 Strategi Harga
Kami menerapkan strategi **Value-Based Pricing combined with Psychological Pricing**. Harga dipasang pada batas psikologis yang dianggap masuk akal bagi mahasiswa dan pekerja muda untuk produk kualitas premium (berkisar antara Rp 149.000 hingga Rp 420.000). Angka ini berada di titik manis (*sweet spot*)—tidak terlalu murah sehingga menurunkan citra premium, dan tidak terlalu mahal untuk daya beli lokal.

### 📣 Strategi Promosi & Diskon
* **Hyper-Local Shipping Subsidy:** Menggunakan insentif "Gratis Ongkir Se-Bandung Raya" untuk menembus pasar lokal dengan cepat.
* **Organic Social Traffic Loop:** Memanfaatkan konten transisi fesyen di TikTok dan YouTube Shorts yang mengarahkan penonton langsung ke tautan toko digital (*Lynk.id / Website*).
* **Urgency & Scarcity:** Menampilkan jumlah ulasan yang tinggi pada produk populer di katalog untuk memicu efek FOMO (*Fear of Missing Out*).

---

## 7. Proses Checkout & Simulasi Payment Gateway

Prototipe ini telah dilengkapi dengan alur transaksi otomatis satu halaman (*Single-Page Checkout*) yang mengintegrasikan simulasi gerbang pembayaran modern guna menjamin efisiensi konversi sistem:

[Keranjang Belanja] ➔ [Isi Form Nama/Alamat] ➔ [Pilih Metode Pembayaran] ➔ [Trigger Simulasi API Gateway]


### 💳 Opsi Gateway yang Diintegrasikan:
1.  **Midtrans Automated QRIS:** Simulasi pembayaran instan menggunakan kode QR dinamis yang dapat dipindai oleh dompet digital (DANA, OVO, GoPay) atau m-Banking.
2.  **Midtrans Virtual Account (VA):** Simulasi nomor rekening penagihan khusus otomatis untuk nasabah Bank BCA atau Mandiri.
3.  **PayPal Dummy Sandbox:** Opsi simulasi pembayaran internasional untuk mengakomodasi potensi pengembangan pasar turis asing di masa depan.

Saat pengguna menekan tombol "Proses Bayar Sekarang", fungsi `processCheckout(event)` akan memvalidasi data, mengosongkan keranjang di `localStorage`, dan memunculkan notifikasi simulasi sukses transfer dana.

---

## 8. Rencana SEO, Keamanan, dan Pemeliharaan

### 🔍 Search Engine Optimization (SEO)
* **Semantic HTML5:** Penggunaan tag `<header>`, `<main>`, `<section>`, dan `<footer>` secara disiplin untuk memudahkan robot *crawler* Google mengindeks struktur web toko.
* **Meta Tag Akselerasi:** Pengaturan set karakter UTF-8 dan deskripsi responsif skala *viewport* agar ramah terhadap mesin pencari perangkat bergerak (*Mobile-First Indexing*).

### 🔒 Keamanan Sistem (Security)
* **Client-Side Sandbox Encryption:** Pemanfaatan `localStorage` terisolasi untuk data keranjang belanja milik masing-masing user guna menghindari kebocoran data antar-pengguna di sisi server.
* **Google Tag Manager Isolated Context:** Kode pelacakan eksternal disematkan secara asinkron (`async`) memastikan skrip analitik berjalan di luar jalur eksternal utama, melindungi integritas performa kode inti dari serangan injeksi pihak ketiga.

### 🛠️ Rencana Pemeliharaan (Maintenance)
* *Asynchronous Asset Optimization:* Gambar produk ditarik dari CDN Unsplash global dengan optimasi *query parameter* kompresi (`q=80&w=400`) untuk menjamin kecepatan *load* web tetap di bawah 2 detik.
* *Modular Scripting:* Pemisahan basis data array `products` dari fungsi manipulasi DOM dilakukan agar ke depannya migrasi ke API *Backend* sesungguhnya (Node.js / Laravel) dapat dieksekusi dengan modifikasi minimal.

---

## 9. Rencana Penggunaan Data Analytics

IKHWAN STORE tidak hanya berfungsi sebagai alat transaksi, tetapi juga sebagai instrumen pengumpul data perilaku konsumen untuk dasar pengambilan keputusan bisnis (*Data-Driven Decision Making*):

### 📊 Metrik Utama yang Dilacak (KPIs)
1.  **Cart-to-Detail Ratio:** Mengukur seberapa banyak konsumen yang mengklik foto produk hingga memunculkan modal detail, lalu melanjutkan menekan tombol "Tambah Ke Keranjang". Jika rasio rendah, deskripsi produk atau harga akan dioptimalkan kembali.
2.  **Search Queries Log Analysis:** Menganalisis kata kunci yang diketik konsumen pada kotak pencarian (`#search-input`). Data ini menjadi acuan langsung tim produksi untuk mengetahui pakaian model apa yang sedang dicari pasar namun belum ada di katalog.
3.  **Category Popularity Dropdown Tracker:** Melacak preferensi filter kategori pilihan konsumen (`Atasan` vs `Outerwear`) untuk menentukan alokasi anggaran produksi stok barang (*Inventory Control*) agar tidak terjadi penumpukan stok mati (*deadstock*).
4.  **Google Analytics Traffic Attribution:** Memanfaatkan integrasi `gtag.js` yang terpasang pada
