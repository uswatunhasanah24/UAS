### UAS
### Nama  : USWATUN HASANAH
### Nim   : 312210343
### Kelas : TI.22.A.3
### PACKAGE & MODUL

![WhatsApp Image 2023-01-09 at 00 19 41](https://user-images.githubusercontent.com/115516474/211229781-37737be4-560d-43a9-b658-b1fc1500bfc2.jpeg)

Sudah dibuat Package seperti gambar di atas

![Screenshot (265)](https://user-images.githubusercontent.com/115516474/211229838-27bcb2fc-74f5-491e-b016-f677bcb16b00.png)

`daftar_nilai.py` Berisi Modul Untuk:

*tambah_data

*ubah_data

*hapus_data

*cari_data

`view_nilai.py` Berisi Modul Untuk:

*cetak_daftar_nilai

*cetak_hasil_pencarian

`input_nilai.py` Berisi Modul Untuk:

*input_data(yang meminta pengguna masukkan data)

`main.py` Berisi Program Utama

*Memanggil semua menu yang yang ada

Kemudian saya tlah menyamtukan syntax yang nanti akan menghasilkan semua modul dari `daftar_nilai` yang diantaranya adalah 
(tambah data,ubah data,lihat data,hapus data,dan cari data)

```
from view.input_nilai import *
data={}
class daftarnilai():
    def tambah_data(self):
        tambah_nama = nama()
        tambah_nim = nim()
        tambah_tugas = tugas()
        tambah_uts = uts()
        tambah_uas = uas()
        tambah_akhir = akhir()
        data[tambah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir

    def ubah_data(self):
        ubah_nama = nama()
        if ubah_nama in data.keys():
           
            tambah_nim = nim()
            tambah_tugas = tugas()
            tambah_uts = uts()
            tambah_uas = uas()
            tambah_akhir = akhir()
            data[ubah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir
        else:
            print('data tidak ditemukan !!!')

    def hapus_data(self):
        hapus_nama = nama()
        if hapus_nama in data.keys():
            del data[hapus_nama]
            print('data berhasil di hapus')
        else:
            print('data tidak ditemukan !!!')

    def keluar(self):```
    
  ```
  
### output tambah_data
   
![1](https://user-images.githubusercontent.com/115516474/211230561-4f653657-1c0d-4d3f-a40c-2f6ed6654f72.png)

   

### output daftar_nilai
    
![2](https://user-images.githubusercontent.com/115516474/211230223-c890a9ad-16b6-474c-bfaa-d7071b24edd7.png)

    
### output ubah_data
    
![3](https://user-images.githubusercontent.com/115516474/211230232-218afe23-8f8f-43b9-ab19-f49419d05fe4.png)

![4](https://user-images.githubusercontent.com/115516474/211230236-a4076dba-b4d2-4b09-ac3d-1c356d10451e.png)

### output cari_data
    
![5](https://user-images.githubusercontent.com/115516474/211230252-82f5282b-4aa7-4d80-add6-049f12cca677.png)

 ### output hapus_data

![6](https://user-images.githubusercontent.com/115516474/211230268-e5f90b20-1c5f-43a4-b17a-9c7d45780af8.png)

