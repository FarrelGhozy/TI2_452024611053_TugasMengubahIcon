---
# Tugas Mengubah Ikon Aplikasi
---

| | |
|---|---|
| **Nama** | FarrelGhozy |
| **NIM** | 452024611053 |
| **Kelas** | TI5A2 |

> ⚠️ **Disclaimer:** Aplikasi ini dibuat untuk keperluan tugas mata kuliah Pemrograman Android. Seluruh konten di dalamnya bersifat **dummy/placeholder** dan tidak merepresentasikan aplikasi production maupun layanan sungguhan.

---

## 📱 Tentang Proyek

Proyek ini merupakan implementasi dari **Google Codelab — Mengubah Ikon Aplikasi** menggunakan **Jetpack Compose** dan **Kotlin**. Fokus utama tugas adalah mengganti **launcher icon** aplikasi Android dengan **adaptive icon** menggunakan **Image Asset Studio**.

### Tujuan
- Memahami cara kerja **adaptive icon** (foreground & background layer)
- Mengganti ikon peluncur aplikasi menggunakan **vector drawable**
- Membuat **legacy icon** untuk kompatibilitas versi Android lama

---

## 🎨 Ikon Aplikasi

Ikon baru menggunakan desain **gradient biru ke ungu** dengan foreground **segitiga play putih**, merepresentasikan tema **media streaming**.

| Adaptive Icon | Legacy Icons |
|---|---|
| `drawable/ic_launcher_background.xml` | `mipmap-mdpi/ic_launcher.webp` (48×48) |
| `drawable/ic_launcher_foreground.xml` | `mipmap-hdpi/ic_launcher.webp` (72×72) |
| `mipmap-anydpi-v26/ic_launcher.xml` | `mipmap-xhdpi/ic_launcher.webp` (96×96) |
| `mipmap-anydpi-v26/ic_launcher_round.xml` | `mipmap-xxhdpi/ic_launcher.webp` (144×144) |
| | `mipmap-xxxhdpi/ic_launcher.webp` (192×192) |

---

## 📄 Halaman Aplikasi

Aplikasi memiliki halaman utama **scrollable** dengan konten dummy:

- **Header** — Nama dan NIM mahasiswa
- **Video Player** — Simulasi pemutar video dengan play button
- **Popular Videos** — 3 card thumbnail video
- **Categories** — Filter chip (All, Music, Sports, Gaming, News)
- **About** — Deskripsi aplikasi

> Konten di atas hanyalah **dummy** untuk melengkapi tampilan aplikasi.

---

## 🛠️ Teknologi

| Teknologi | Versi |
|---|---|
| Kotlin | 2.2.10 |
| Android Gradle Plugin | 9.1.1 |
| Compose BOM | 2026.02.01 |
| Material Design 3 | ✅ |
| Adaptive Icons | ✅ (API 26+) |

---

## 🚀 Cara Menjalankan

1. Buka proyek di **Android Studio**
2. Tunggu proses sinkronisasi Gradle
3. Klik **Run** ▶️ atau jalankan:
   ```bash
   ./gradlew assembleDebug
   ```
4. Instal APK pada emulator/device (min SDK: 35)

---

## 🎥 Demo Aplikasi

<video src="assets/demo.mp4" controls width="100%"></video>

> Upload file `demo.mp4` ke folder `assets/` untuk menampilkan video.

---

<p align="center">
  <i>Tugas Pemrograman Android — Semester 5</i>
</p>
