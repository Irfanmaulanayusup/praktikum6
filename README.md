# praktikum_6

Nama: Irfan Maulana Yusup

NIM: 312410488

Kelas: TI.24.A.5

## Ini penjelasan dari program yang saya buat

1. Mendefinisikan Daftar:
```python
daftar_mahasiswa = []
```

Daftar kosong mahasiswa dibuat untuk menyimpan nama-nama mahasiswa.

2. Fungsi Untuk Menambah Mahasiswa:
```python
def tambah(nama):
daftar_mahasiswa.append(nama)
print(f"Mahasiswa dengan nama {nama} telah ditambahkan.")
```

Fungsi tambah menerima parameter nama, menambahkannya ke daftar mahasiswa, dan mencetak pesan konfirmasi.

3. Fungsi Untuk Menampilkan Mahasiswa
```python
def tampilkan():
if daftar_mahasiswa:
print("Daftar Mahasiswa:")
for i, nama in enumerate(daftar_mahasiswa, 1):
print(f"{i}. {nama}")
else:
print("Tidak ada data mahasiswa.")
```

Fungsi tampilkan memeriksa apakah daftar mahasiswa tidak kosong, kemudian mencetak daftar mahasiswa beserta nomor urut mereka. Jika daftar kosong, mencetak pesan bahwa tidak ada data mahasiswa.

4. Fungsi Untuk Menghapus Mahasiswa:
```python
def hapus(nama):
if nama in daftar_mahasiswa:
daftar_mahasiswa.remove(nama)
print(f"Mahasiswa dengan nama {nama} telah dihapus.")
else:
print(f"Mahasiswa dengan nama{nama} tidak ditemukan.")
```

Fungsi hapus memeriksa apakah nama mahasiswa ada dalam daftar mahasiswa. Jika ditemukan, nama tersebut dihapus dan mencetak pesan Mahasiswa dengan nama (nama yang dihapus) telah dihapus. Jika tidak ditemukan, mencetak pesan Mahasiswa dengan nama (nama yang dihapus) tidak ditemukan.

5. Fungsi Untuk Mengubah Nama Mahasiswa:
```python
def ubah(nama_lama, nama_baru):
if nama_lama in daftar_mahasiswa:
index = daftar_mahasiswa.index(nama_lama)
daftar_mahasiswa[index] = nama_baru
print(f"Mahasiswa dengan nama {nama_lama} telah diubah menjadi {nama_baru}.")
else:
print(f"Mahasiswa dengan nama {nama_lama} tidak ditemukan.")
```

Fungsi ubah memeriksa apakah nama lama ada dalam daftar mahasiswa. Jika ditemukan, nama tersebut diubah menjadi nama baru dan mencetak pesan Mahasiswa dengan nama (nama lama) telah diubah menjadi (nama baru). Jika tidak ditemukan, mencetak pesan Mahasiswa dengan nama (nama lama) tidak ditemukan.

6. Contoh Penggunaan:
```python
tambah("Rizal")
tambah("Nabilah")
tambah("Mela")
tambah("Putri")
tambah("Reza")
tampilkan()
hapus("Nabilah")
tampilkan()
ubah("Mela", "Mia")
tampilkan()

```

Baris-baris ini menunjukkan bagaimana cara menggunakan fungsi-fungsi tersebut:
- Menambah mahasiswa: Rizal, Nabilah, Putri, Mela, dan Reza.
- Menampilkan daftar mahasiswa.
- Menghapus Nabilah dari daftar mahasiswa dan menampilkan daftar mahasiswa yang telah diperbarui.
- Mengubah Mela menjadi Mia dan menampilkan daftar mahasiswa yang telah diperbarui.

## Ini hasil/output dari program yang saya buat

![gambar](daftar_mahasiswa.png)
![gambar](daftar_mahasiswa3.png)

## Ini penjelasan dari flowchart yang saya buat

1.Mulai: Proses dimulai dari langkah ini.

2.Pembuatan Daftar Kosong: Membuat sebuah daftar kosong yang dinamakan daftar_mahasiswa.

3.Penambahan Data Mahasiswa: Menambahkan nama-nama mahasiswa seperti Rizal, Nabilah, Mela, Reza, dan Putri ke dalam daftar_mahasiswa.

4.Penyimpanan Data: Menyimpan nama-nama mahasiswa yang telah ditambahkan ke dalam daftar_mahasiswa.

5.Pemeriksaan Keadaan Daftar: Memeriksa apakah daftar_mahasiswa kosong:

Jika kosong, tampilkan pesan "Tidak ada data mahasiswa".

Jika tidak kosong, tampilkan isi dari daftar_mahasiswa.

6.Pengecekan Nama Nabilah: Memeriksa apakah nama Nabilah terdapat dalam daftar_mahasiswa:

Jika ada, maka hapus nama Nabilah dari daftar_mahasiswa.

Jika tidak ada, tampilkan pesan "Mahasiswa dengan nama Nabilah tidak ditemukan".

7.Penyimpanan Perubahan Data: Menyimpan data yang telah diperbarui ke dalam daftar_mahasiswa.
