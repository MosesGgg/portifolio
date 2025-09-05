# Portfolio Website - Christian Moses Aryadi

Website portofolio pribadi modern dan responsif dengan animasi yang memukau untuk Christian Moses Aryadi.

## 🚀 Fitur Utama

### ✨ Animasi & Interaktivitas
- **Typing Effect** - Animasi mengetik nama di Hero Section
- **Scroll Animations** - Animasi fade-in dan slide-in saat scroll menggunakan AOS.js
- **Progress Bars** - Animasi progress bar untuk skill dengan persentase
- **Hover Effects** - Efek hover pada cards, buttons, dan project items
- **Smooth Scrolling** - Navigasi halus antar section
- **Parallax Effects** - Efek parallax pada background shapes

### 📱 Responsive Design
- **Mobile-First** - Desain responsif untuk semua ukuran layar
- **Breakpoints** - Optimized untuk desktop, tablet, dan mobile
- **Touch-Friendly** - Interface yang ramah untuk perangkat sentuh

### 🎨 Desain Modern
- **Gradient Backgrounds** - Warna gradient yang menarik
- **Card-Based Layout** - Layout berbasis card yang clean
- **Modern Typography** - Font Poppins yang elegan
- **Color Scheme** - Skema warna yang konsisten dan profesional

### 📋 Section Lengkap
1. **Hero Section** - Nama dengan typing effect dan foto profil
2. **About Section** - Informasi personal dengan layout grid
3. **Skills Section** - Keahlian dengan progress bars dan tags
4. **Projects Section** - Project dengan hover overlay dan tech stack
5. **Contact Section** - Form kontak dengan validasi dan social links

## 📁 Struktur File

```
portfolio-christian/
├── index.html          # File HTML utama
├── css/
│   └── style.css       # Stylesheet utama
├── js/
│   └── script.js       # JavaScript untuk animasi dan interaktivitas
├── images/             # Folder untuk gambar (kosong, menggunakan placeholder)
├── assets/             # Folder untuk asset tambahan
└── README.md           # Dokumentasi ini
```

## 🛠️ Teknologi yang Digunakan

- **HTML5** - Struktur semantic yang modern
- **CSS3** - Styling dengan CSS Variables, Flexbox, dan Grid
- **JavaScript (ES6+)** - Interaktivitas dan animasi
- **AOS.js** - Animate On Scroll library
- **Font Awesome** - Icon library
- **Google Fonts** - Font Poppins

## 🚀 Cara Menjalankan di XAMPP

### Langkah 1: Persiapan XAMPP
1. Pastikan XAMPP sudah terinstall di komputer Anda
2. Jalankan XAMPP Control Panel
3. Start service **Apache**

### Langkah 2: Deploy Website
1. Copy seluruh folder `portfolio-christian` ke dalam folder `htdocs` XAMPP
   - Lokasi default: `C:\xampp\htdocs\` (Windows) atau `/opt/lampp/htdocs/` (Linux)
2. Pastikan struktur folder seperti ini:
   ```
   htdocs/
   └── portfolio-christian/
       ├── index.html
       ├── css/
       ├── js/
       └── ...
   ```

### Langkah 3: Akses Website
1. Buka browser (Chrome, Firefox, Safari, dll.)
2. Ketik URL: `http://localhost/portfolio-christian/`
3. Website akan terbuka dan siap digunakan!

## 🎯 Fitur JavaScript

### Typing Effect
- Animasi mengetik otomatis dengan multiple text
- Efek cursor berkedip
- Loop infinite dengan pause

### Form Validation
- Validasi real-time untuk semua field
- Notifikasi error dan success
- Animasi loading saat submit

### Scroll Animations
- Intersection Observer API untuk performa optimal
- Stagger animations untuk cards
- Progress bar animation trigger

### Navigation
- Active link highlighting
- Mobile hamburger menu
- Smooth scroll ke section

## 🎨 Customization

### Mengubah Warna
Edit CSS variables di bagian `:root` dalam `style.css`:
```css
:root {
    --primary-color: #4f46e5;    /* Warna utama */
    --secondary-color: #06b6d4;  /* Warna sekunder */
    --accent-color: #8b5cf6;     /* Warna aksen */
}
```

### Mengubah Konten
1. **Data Personal** - Edit bagian About section di `index.html`
2. **Skills** - Ubah progress percentage di `data-progress` attribute
3. **Projects** - Tambah/edit project cards di Projects section
4. **Contact Info** - Update informasi kontak di Contact section

### Menambah Gambar
1. Simpan gambar di folder `images/`
2. Ganti URL placeholder dengan path gambar:
   ```html
   <!-- Dari -->
   <img src="https://via.placeholder.com/400x400/4f46e5/ffffff?text=CM" alt="...">
   
   <!-- Ke -->
   <img src="images/profile.jpg" alt="...">
   ```

## 📱 Browser Support

Website ini kompatibel dengan:
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Troubleshooting

### Website tidak muncul
- Pastikan Apache service di XAMPP sudah running
- Check URL: `http://localhost/portfolio-christian/`
- Pastikan file `index.html` ada di folder yang benar

### Animasi tidak berfungsi
- Pastikan koneksi internet aktif (untuk load AOS.js dan Font Awesome)
- Check browser console untuk error JavaScript
- Pastikan semua file CSS dan JS ter-load dengan benar

### Layout rusak di mobile
- Clear browser cache
- Test di browser yang berbeda
- Pastikan viewport meta tag ada di HTML

## 🎉 Easter Egg

Website ini memiliki easter egg! Coba ketik **Konami Code** di keyboard:
`↑ ↑ ↓ ↓ ← → ← → B A`

## 📞 Support

Jika ada pertanyaan atau masalah, silakan hubungi:
- **Email**: christian.moses@email.com
- **GitHub**: [Link akan ditambahkan]
- **LinkedIn**: [Link akan ditambahkan]

---

**Dibuat dengan ❤️ oleh Christian Moses Aryadi**
*Developer muda berusia 17 tahun dari Tangerang*

