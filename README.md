# DessertRecycleView - Modul 2 Materi 6 (PAM)

Proyek Android modifikasi halaman tampilan Droid Desserts menjadi RecyclerView interaktif dengan dynamic tinted circular background pada gambar dessert.

## Informasi Mahasiswa
- **Nama**: Ramadan Nurwahid
- **NIM**: 1237050065
- **Mata Kuliah**: Pemrograman Aplikasi Mobile (PAM)
- **Materi**: Materi 6 - RecyclerView (Modul 2 & Modul 3)

## Fitur & Komponen Utama
1. **RecyclerView**: Menampilkan daftar dessert dengan performa tinggi dan memori efisien.
2. **CoordinatorLayout & Edge-to-Edge**: Tampilan modern mengikuti guideline Material Design dan Android 14/15.
3. **Custom Adapter (`DessertAdapter`)**: Menangani binding data, gambar (`ImageView`), dan deskripsi (`TextView`).
4. **Dynamic Background Tint**: Mewarnai `FrameLayout` (`circle_background.xml`) secara dinamis sesuai kode HEX warna masing-masing dessert menggunakan `GradientDrawable`.
5. **Data Items**:
   - Donut: `#C1E8C5` (Mint Green)
   - Ice Cream Sandwich: `#BBE0F8` (Light Blue)
   - Froyo: `#E4BCDF` (Soft Lavender/Pink)
