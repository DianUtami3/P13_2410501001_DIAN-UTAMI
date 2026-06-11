## Nama : Dian Utami
## NIM: 2410501001

# Latihan 13 Mobile - Animated API, Swipe Gesture, dan Background Task

Project ini dibuat menggunakan **React Native dengan Expo** untuk memenuhi tugas **Pertemuan 13 Pemrograman Mobile Lanjut**. Aplikasi ini berisi implementasi beberapa topik lanjutan, yaitu animasi menggunakan Animated API, gesture swipe pada list item, penyimpanan data quote menggunakan AsyncStorage, serta simulasi background task agar tetap bisa dijalankan di Expo Go.

## Fitur Aplikasi

Aplikasi ini memiliki beberapa fitur utama:

1. **Animated Card**
   - Kartu muncul dengan efek fade-in dari bawah.
   - Kartu dapat ditekan untuk menghasilkan animasi bounce.
   - Kartu dapat ditekan lama untuk melakukan rotasi 360 derajat.

2. **Swipeable List Item**
   - Item dapat di-swipe ke kanan untuk melakukan aksi Archive.
   - Item dapat di-swipe ke kiri untuk melakukan aksi Delete.
   - Jika item di-swipe jauh ke kiri, item akan otomatis terhapus dari daftar.

3. **Quote dengan AsyncStorage**
   - Aplikasi dapat mengambil quote dari API.
   - Quote yang berhasil diambil akan disimpan ke AsyncStorage.
   - Quote terakhir akan tetap tampil ketika aplikasi dibuka kembali.

4. **Simulasi Background Task**
   - Background task disimulasikan agar aplikasi dapat berjalan dengan aman di Expo Go.
   - Simulasi ini menyimpan data quote ke AsyncStorage.
   - Untuk background task asli, aplikasi perlu menggunakan development build karena Expo Go memiliki keterbatasan pada fitur background task.

5. **Pertanyaan Refleksi**
   - Aplikasi juga menampilkan jawaban refleksi terkait Animated API, Reanimated 2, background task, server-side validation, dan lazy loading image.

## Teknologi yang Digunakan

Project ini menggunakan beberapa teknologi berikut:

- React Native
- Expo
- JavaScript
- React Hooks
- Animated API
- PanResponder
- AsyncStorage

## Struktur Folder

Struktur folder pada project ini adalah sebagai berikut:

```bash
latihan13mobile
│
├── App.js
├── package.json
│
└── src
    ├── components
    │   ├── AnimatedCard.js
    │   └── SwipeableListItem.js
    │
    └── tasks
        └── quoteTask.js
