A sample command-line application with an entrypoint in `bin/`, library code
in `lib/`, and example unit test in `test/`.

### Aplikasi Penghitung Gaji Karyawan Sederhana

### Identitas Mahasiswa
Nama  : Derita Saputri Ismail
NPM   : 07352211066
Kelas : 5IF3

### Deskripsi Program
Program ini dibuat untuk menghitung gaji bersih karyawan berdasarkan:
- Nama karyawan (String)
- Jumlah jam kerja (int)
- Upah per jam (double)
- Status karyawan (bool: `true = tetap`, `false = kontrak`)

Program akan menghitung:
- Gaji kotor = jam kerja × upah per jam
- Pajak = 10% jika karyawan tetap, 5% jika kontrak
- Gaji bersih = gaji kotor – pajak

### Cara Menjalankan Program
1. Pastikan sudah menginstal [Dart SDK](https://dart.dev/get-dart).
2. Masuk ke folder `src`:
   ### powershell
   cd saputri_project
   cd src
   dart tugas.dart