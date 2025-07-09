# 🖼️ Penghilang Noise Gambar Pro

Aplikasi web canggih untuk menghilangkan noise dari gambar menggunakan berbagai algoritma pemrosesan gambar yang sophisticated. Aplikasi ini memiliki antarmuka yang modern dan user-friendly dengan fitur drag-and-drop yang mudah digunakan.

## ✨ Fitur Utama

- **🎯 Tiga Algoritma Pemrosesan Canggih**
  - **Advanced Filter**: Algoritma penghilang noise yang sangat kuat dengan preservasi detail
  - **Multi-Pass Filter**: Proses berlapis untuk hasil maksimal ⚠️ **(Proses sangat lama)**
  - **AI-Enhanced Filter**: Algoritma cerdas dengan deteksi noise otomatis

- **🎛️ Kontrol Parameter Lengkap**
  - Kekuatan Noise Reduction (50-95%)
  - Preservasi Detail (30-90%)
  - Kelembutan (20-80%)
  - Ketajaman (0-100%)

- **📊 Statistik Real-time**
  - Persentase pengurangan noise
  - Skor kualitas PSNR
  - Sharpness score
  - Waktu pemrosesan

- **🎨 Antarmuka Modern**
  - Desain gradient yang memukau
  - Drag & drop file upload
  - Responsif untuk semua perangkat
  - Animasi smooth dan interaktif

## 🚀 Cara Penggunaan

1. **Upload Gambar**
   - Drag & drop gambar ke area upload, atau
   - Klik tombol "Pilih Gambar" untuk browse file
   - Format yang didukung: JPG, PNG, GIF, BMP

2. **Pilih Algoritma**
   - **Advanced Filter**: Untuk noise reduction standar yang cepat
   - **Multi-Pass Filter**: Untuk hasil terbaik (⚠️ *membutuhkan waktu lama*)
   - **AI-Enhanced Filter**: Untuk deteksi noise otomatis

3. **Sesuaikan Parameter**
   - Atur slider sesuai kebutuhan
   - Preview nilai real-time
   - Eksperimen dengan kombinasi yang berbeda

4. **Proses Gambar**
   - Klik tombol "🔧 Proses Gambar"
   - Tunggu hingga pemrosesan selesai
   - Lihat hasil perbandingan

5. **Download Hasil**
   - Klik "💾 Download Hasil" untuk menyimpan
   - Atau "🔄 Proses Gambar Baru" untuk mengulang

## ⚠️ Peringatan Penting

### Multi-Pass Filter
> **PERHATIAN**: Algoritma Multi-Pass Filter menggunakan proses berlapis yang sangat intensif dan membutuhkan waktu pemrosesan yang **SANGAT LAMA**. Disarankan untuk:
> - Menggunakan gambar dengan resolusi kecil-menengah
> - Mempersiapkan waktu tunggu yang cukup
> - Tidak menutup browser selama proses berlangsung
> - Gunakan untuk gambar dengan noise yang sangat berat saja

## 🔧 Algoritma yang Digunakan

### 1. Advanced Filter
- **Bilateral Filtering**: Preservasi edge sambil mengurangi noise
- **Gaussian Blur**: Smoothing adaptif
- **Weighted Averaging**: Penghilangan noise berbasis bobot
- **Unsharp Masking**: Enhancement detail

### 2. Multi-Pass Filter
- **Pass 1**: Non-Local Means Denoising
- **Pass 2**: Edge-preserving smoothing
- **Pass 3**: Detail enhancement
- **Iterative Processing**: Multiple passes untuk hasil optimal

### 3. AI-Enhanced Filter
- **Noise Pattern Detection**: Deteksi otomatis pola noise
- **Adaptive Filtering**: Filter yang menyesuaikan dengan area gambar
- **Smart Kernel Selection**: Pemilihan kernel berdasarkan noise level
- **Contextual Processing**: Pemrosesan berdasarkan konteks gambar

## 📊 Metrik Kualitas

- **Noise Reduction**: Persentase pengurangan noise dari gambar original
- **PSNR (Peak Signal-to-Noise Ratio)**: Ukuran kualitas gambar dalam dB
- **Sharpness Score**: Tingkat ketajaman gambar hasil
- **Processing Time**: Waktu yang diperlukan untuk pemrosesan

## 🛠️ Teknologi yang Digunakan

- **HTML5 Canvas**: Untuk manipulasi gambar pixel-level
- **JavaScript ES6+**: Algoritma pemrosesan gambar
- **CSS3**: Styling modern dengan gradient dan animasi
- **FileReader API**: Upload dan pembacaan file
- **ImageData API**: Manipulasi data gambar

## 🎨 Fitur Desain

- **Gradient Background**: Efek visual yang menarik
- **Glassmorphism**: Efek kaca transparan
- **Smooth Animations**: Transisi yang halus
- **Responsive Design**: Tampilan optimal di semua perangkat
- **Interactive Elements**: Hover effects dan feedback visual

## 📱 Kompatibilitas

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Instalasi

1. Clone repository:
```bash
git clone https://github.com/username/penghilang-noise-gambar-pro.git
```

2. Buka file `index.html` di browser modern

3. Mulai menggunakan aplikasi!

## 📝 Lisensi

Project ini dilisensikan under MIT License - lihat file [LICENSE](LICENSE) untuk detail.

## 🤝 Kontribusi

Kontribusi sangat diterima! Silakan:

1. Fork repository
2. Buat feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buka Pull Request

## 📧 Kontak

Jika ada pertanyaan atau saran, jangan ragu untuk membuka issue di repository ini.

---

⭐ **Jangan lupa untuk memberikan star jika project ini bermanfaat!**
