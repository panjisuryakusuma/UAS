# UAS
# PACKAGE & MODULE
**saya di beri tugas UAS ini  dengan struktur seperti sebagai berikut:**

![soal uas](https://user-images.githubusercontent.com/93035757/149618916-d7707552-7229-4def-930f-5a706dd00ac1.png)
 
* ``daftar_nilai.py`` berisi modul untuk  :
    * tambah_data
    * ubah_data
    * hapus_data
    * cari_data 
* ``view_nilai.py`` berisi modul untuk : 
    * cetak_daftar_nilai 
    * cetak_hasil_pencarian
* ``input_nilai.py`` berisi modul untuk :
    * input_data (yang meminta pengguna memasukkan data).
* ``main.py`` berisi program utama (menu pilihan yang memanggil semua menu yang ada).

* hasil package yang saya buat sebagai berikut :


![screnshoot package](https://user-images.githubusercontent.com/93035757/149619102-a4bdde61-6bbc-4e50-8aca-2c4dcabf3532.png)

* pertama saya telah menyantumkan beberapa syntax yang nantinya akan menghasilkan semua modul dari package Daftar_Nilai yang diantaranya adalah (Tambah Data, Ubah Data, Hapus Data, Dan Cari Data)

```py

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

    def keluar(self):
    
```
     
    
    
    

* **Output tambah_data**
  
   <img width="784" alt="opsiTambah" src="https://user-images.githubusercontent.com/56913656/71645566-d7b45a80-2d0c-11ea-95f4-64a19c61d4d1.png">

* **Output daftar_nilai**

  <img width="418" alt="opsiLihat" src="https://user-images.githubusercontent.com/56913656/71645584-164a1500-2d0d-11ea-99c9-51c4636c7cda.png">

* **Output ubah_data**

  <img width="454" alt="opsiUbah" src="https://user-images.githubusercontent.com/56913656/71645599-3ed20f00-2d0d-11ea-8649-fec892b0f382.png">

* **Output Cari_data**

  <img width="428" alt="opsiCari" src="https://user-images.githubusercontent.com/56913656/71645619-704ada80-2d0d-11ea-9d52-eb1c26fcf281.png">

* **Output Hapus_data**

  <img width="421" alt="opsiHapus" src="https://user-images.githubusercontent.com/56913656/71645628-8f496c80-2d0d-11ea-994e-9d5de3582049.png">

## **TERIMA KASIH**
