# Program Daftar Nilai Mahasiswa
Program ini digunakan untuk mengelola data mahasiswa, menghitung nilai akhir, dan menampilkan daftar mahasiswa dalam format tabel. berikut perintah programnya :

![Screenshot 2024-11-21 210242](https://github.com/user-attachments/assets/f536eeb4-9ab8-428e-a3f0-bf77a60abff2)

## Fungsi `hitung_nilai_akhir`

### Tujuan

Menghitung nilai akhir mahasiswa berdasarkan nilai tugas, UTS, dan UAS.

### Parameter

- **nilai_tugas**: Nilai tugas mahasiswa (float).
- **nilai_uts**: Nilai UTS mahasiswa (float).
- **nilai_uas**: Nilai UAS mahasiswa (float).

### Rumus

Nilai akhir dihitung dengan rumus:
Akhir = (Tugas * 0.3) + (UTS * 0.35) + (UAS * 0.35)

### Return

Mengembalikan nilai akhir yang telah dihitung (float).

## Inisialisasi Data

- data_mahasiswa : Menyimpan data mahasiswa dengan NIM sebagai kunci dan informasi mahasiswa (nama, nilai tugas, UTS, UAS, dan nilai akhir) sebagai nilai.

## Input Data Mahasiswa

Menggunakan while True untuk membuat loop yang terus berulang hingga pengguna memilih untuk berhenti.
Program meminta pengguna untuk memasukkan data mahasiswa dalam format berikut:
1. **Nama**: Nama lengkap mahasiswa.
2. **NIM**: Nomor Induk Mahasiswa.
3. **Nilai Tugas**: Nilai yang diperoleh dari tugas.
4. **Nilai UTS**: Nilai yang diperoleh dari Ujian Tengah Semester.
5. **Nilai UAS**: Nilai yang diperoleh dari Ujian Akhir Semester.

Menggunakan fungsi hitung_nilai_akhir untuk menghitung nilai akhir.

## Menyimpan Data

Menyimpan data mahasiswa beserta nilai akhirnya ke dalam dictionary data_mahasiswa dengan NIM sebagai kuncinya.

## Menanyakan Tambah Data

Menanyakan kepada pengguna apakah ingin menambahkan data lagi. jika pengguna ingin berhenti, maka loop akan berakhir.

## Menampilkan Daftar Mahasiswa

Setelah pengguna memilih untuk tidak menambah data lagi, program menampilkan daftar semua mahasiswa yang telah dimasukkan dalam format tabel. Tabel mencakup:
- **No**: Nomor urut mahasiswa.
- **Nama**: Nama lengkap mahasiswa.
- **NIM**: Nomor Induk Mahasiswa.
- **Tugas**: Nilai tugas mahasiswa.
- **UTS**: Nilai Ujian Tengah Semester.
- **UAS**: Nilai Ujian Akhir Semester.
- **Akhir**: Nilai akhir yang telah dihitung.

### Contoh Output

![Screenshot 2024-11-21 210830](https://github.com/user-attachments/assets/dd0a7447-c678-4b6b-9097-04f456fdb677)

### Flowchart

![Screenshot 2024-11-21 223413](https://github.com/user-attachments/assets/c703a7b8-5101-4b67-96f2-d210302db151)

