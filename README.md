# Aplikasi Pengelolaan Catatan Sederhana dengan React Native

Proyek ini merupakan aplikasi pengelolaan catatan sederhana yang dikembangkan menggunakan framework React Native. Aplikasi ini memungkinkan pengguna untuk menambahkan, mengedit, dan menghapus catatan.

## Fitur Aplikasi

- **Menambahkan Catatan**: Pengguna dapat menambahkan catatan baru dengan mengisi judul dan deskripsi.
- **Mengedit Catatan**: Pengguna dapat mengedit catatan yang sudah ada dengan mengubah judul dan deskripsi.
- **Menghapus Catatan**: Pengguna dapat menghapus catatan yang tidak diinginkan.

## Komponen Utama

1. **Home.js**: Menampilkan daftar catatan yang sudah ada. Terdapat tombol untuk menambahkan catatan baru dan opsi untuk mengedit atau menghapus catatan yang ada.
2. **AddNote.js**: Formulir untuk menambahkan catatan baru dengan input untuk judul dan deskripsi.
3. **EditNote.js**: Formulir untuk mengedit catatan yang sudah ada. Menggunakan input untuk judul dan deskripsi yang diisi dengan data catatan yang dipilih.

## Komponen Tambahan

1. **CustomTextInput**: Komponen input teks kustom yang digunakan untuk menerima input judul dan deskripsi dari pengguna.
2. **CustomButton**: Komponen tombol kustom yang digunakan untuk berbagai aksi seperti menyimpan catatan, kembali ke halaman utama, mengedit, dan menghapus catatan.

## State dan Props

### State

- `currentPage`: Menyimpan informasi halaman saat ini (home, add, edit).
- `noteList`: Menyimpan daftar catatan yang ada.
- `noteToEdit`: Menyimpan catatan yang dipilih untuk diedit.

### Props

- `setCurrentPage`: Fungsi untuk mengubah halaman saat ini.
- `addNote`: Fungsi untuk menambahkan catatan baru ke dalam `noteList`.
- `editNote`: Fungsi untuk mengedit catatan yang ada di `noteList`.
- `deleteNote`: Fungsi untuk menghapus catatan dari `noteList`.
- `noteList`: Data daftar catatan yang ada, digunakan untuk menampilkan catatan di halaman home.
- `noteToEdit`: Data catatan yang dipilih untuk diedit, digunakan di halaman edit.
- `setNoteToEdit`: Fungsi untuk menyimpan catatan yang dipilih untuk diedit.

## Struktur Komponen

- **App.js**: Komponen utama yang mengelola state aplikasi dan merender komponen halaman berdasarkan state `currentPage`.
- **CurrentPageWidget**: Komponen yang merender halaman sesuai dengan nilai `currentPage`.

## Penggunaan

1. **Menambahkan Catatan**: Tekan tombol "Tambahkan Note" di halaman utama dan akan diarahkan ke halaman `AddNote`.
2. **Mengedit Catatan**: Tekan tombol "Ubah" pada catatan di halaman utama dan akan diarahkan ke halaman `EditNote` dengan data catatan yang dipilih.
3. **Menghapus Catatan**: Tekan tombol "Hapus" pada catatan di halaman utama, dan catatan tersebut akan dihapus dari `noteList`.

Aplikasi ini sederhana namun fungsional, memberikan dasar yang baik untuk memahami konsep state dan props dalam pengembangan aplikasi React Native.

## Instalasi

1. Clone repository ini:
   ```bash
   git clone https://github.com/username/repository.git

2. Masuk direktori proyek:
   ```bash
   cd repository

2. Instal dependencies:
   ```bash
   npm install

2. Jalankan aplikasi:
   ```bash
   npm start


## Authors

- [BagusErwanto](https://github.com/volumeee)

