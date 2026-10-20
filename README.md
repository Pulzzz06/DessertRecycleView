# Droid Desserts 🍩🍦🍨

Proyek aplikasi Android berbasis **Kotlin/Java** yang menampilkan katalog makanan penutup bertema nama kode rilis Android legendaris (*Donut*, *Ice Cream Sandwich*, dan *Froyo*). Aplikasi ini dirancang untuk mendemonstrasikan penyusunan tata letak antarmuka (UI Layout), penataan aset visual (*circular images*), serta penanganan interaksi pengguna (*user event handling*) pada platform Android.

---

## 📱 Gambaran Proyek

Aplikasi **Droid Desserts** menyajikan daftar pilihan hidangan penutup yang dilengkapi dengan ikon visual melingkar (*circular avatar/badge*) berlatar warna pastel yang serasi, nama hidangan, serta deskripsi singkat masing-masing menu.

### Daftar Menu yang Ditampilkan:
1. **Donut**  
   *Deskripsi:* *"Donuts are glazed and sprinkled with candy."*  
   *Aksen Visual:* Ikon donat dengan latar belakang lingkaran hijau muda pastel.
2. **Ice Cream Sandwiches**  
   *Deskripsi:* *"Ice cream sandwiches have chocolate wafers and vanilla filling."*  
   *Aksen Visual:* Ikon sandwich es krim dengan latar belakang lingkaran biru muda pastel.
3. **Froyo**  
   *Deskripsi:* *"Froyo is premium self-serve frozen yogurt."*  
   *Aksen Visual:* Ikon yogurt beku dengan latar belakang lingkaran ungu muda pastel.

---

## ✨ Fitur Utama

- **Desain UI Bersih & Rapi:** Penerapan komponen tata letak adaptif menggunakan `ConstraintLayout` / `LinearLayout` atau `RecyclerView`.
- **Aset Grafis Melingkar:** Penggunaan latar belakang berbentuk lingkaran (*circle shape drawable* atau `ShapeableImageView`) untuk menonjolkan visual hidangan.
- **Interaksi Pengguna (Event Listener):** Dukungan klik pada setiap item/gambar untuk memicu aksi (seperti pesan konfirmasi `Toast`, `Snackbar`, atau navigasi ke rincian pesanan).

---

## 📂 Struktur Berkas Proyek

```
DroidDesserts/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/droiddesserts/
│   │   │   │   ├── MainActivity.kt / MainActivity.java   # Logika interaksi & kontrol tampilan utama
│   │   │   │   └── DessertModel.kt                      # Model data deskripsi makanan penutup (opsional)
│   │   │   └── res/
│   │   │       ├── drawable/
│   │   │       │   ├── donut_circle.xml                 # Shape drawable latar belakang donat
│   │   │       │   ├── sandwich_circle.xml              # Shape drawable latar belakang es krim
│   │   │       │   ├── froyo_circle.xml                 # Shape drawable latar belakang froyo
│   │   │       │   ├── donut.png                        # Asset gambar donat
│   │   │       │   ├── ice_cream_sandwich.png           # Asset gambar es krim sandwich
│   │   │       │   └── froyo.png                        # Asset gambar froyo
│   │   │       ├── layout/
│   │   │       │   └── activity_main.xml                # Layout antarmuka layar Droid Desserts
│   │   │       └── values/
│   │   │           ├── colors.xml                       # Definisi palet warna tema & pastel
│   │   │           ├── strings.xml                      # String teks menu & deskripsi
│   │   │           └── themes.xml                       # Tema aplikasi
│   └── build.gradle.kts (atau build.gradle)
```

---

## 🛠️ Teknologi & Prasyarat

- **IDE:** Android Studio (versi Flamingo, Hedgehog, Koala, atau yang lebih baru)
- **Bahasa Pemrograman:** Kotlin / Java
- **Minimum SDK:** API Level 21 (Android 5.0 Lollipop) atau lebih tinggi
- **Target SDK:** API Level 34+
- **Komponen Utama:**
  - `androidx.appcompat:appcompat`
  - `com.google.android.material:material`
  - `androidx.constraintlayout:constraintlayout`

---

## 🚀 Panduan Menjalankan Aplikasi

1. **Clone Repositori:**
   ```bash
   git clone https://github.com/username/droid-desserts.git
   ```
2. **Buka Proyek:**
   - Jalankan Android Studio.
   - Pilih **Open**, lalu arahkan ke folder direktori `DroidDesserts`.
3. **Sinkronisasi Gradle:**
   - Tunggu proses *Gradle Sync* selesai mengunduh seluruh dependensi yang diperlukan.
4. **Jalankan Aplikasi:**
   - Sambungkan perangkat fisik Android melalui USB Debugging atau jalankan Android Virtual Device (AVD / Emulator).
   - Tekan tombol **Run** (`Shift + F10`) pada toolbar Android Studio.

---

## 📸 Tangkapan Layar Antarmuka

| Layar Utama Droid Desserts |
| :-------------------------: |
| *(Sematkan tangkapan layar aplikasi Anda di sini)* |

---

## 📄 Catatan Pengerjaan & Implementasi

- Teks judul halaman menggunakan gaya terpusat: `Droid Desserts`.
- Format penulisan teks deskripsi terstruktur rapi di sebelah kanan setiap gambar item.
- Nilai teks, warna latar, dan dimensi disarankan didefinisikan secara terpusat pada direktori `res/values/` (`strings.xml` dan `colors.xml`) demi mematuhi kaidah *best practices* pengembangan aplikasi Android.