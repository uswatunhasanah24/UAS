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
from model.daftar_nilai import daftarnilai
from view.view_nilai import mencari
while True:
    b = daftarnilai()
    c = mencari()
    print('tambah\t(1)\nubah\t(2)\ncari\t(3)\nhapus\t(4)\nlihat\t(5)')
    a = input('Masukkan pilihan > ')
    if (a=="1"):
        b.tambah_data()
    elif (a=="2"):
        b.ubah_data()
    elif (a=="3"):
        c.cetak_hasil_pencarian()
    elif (a=="4"):
        b.hapus_data()
    elif (a=="5"):
        c.cetak_daftar_nilai()
    else :
        break
    
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

