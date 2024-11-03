Tentang repositori ini
---
Load Balancing dalam Komputasi Jaringan

Pada file `Readme.md` ini *submission* **harus** memiliki bagian/struktur seperti berikut:
1. Deskripsi repositori
2. Direktori `codes`
3. Direktori `documentation`
4. Informasi anggota kelompok

:warning: **Seluruh** Section di atas bersifat pengantar dan *hendaknya* dihapus ketika melakukan *submission* yang sebenarnya. 

:warning: *Edit* seluruh Section di bawah ini sesuai kebutuhan

# Deskripsi repositori
 > Berisi penjelasan struktur repositori, bersifat seperti daftar isi

Repositori ini merupakan tugas mandiri matakuliah Komputasi berbasis Jaringan dengan tugas implementasi sederhana dari konsep load balancing menggunakan Python socket programming. Proyek ini bertujuan untuk memahami dan menerapkan teknik load balancing dalam mendistribusikan request client ke beberapa server worker melalui server broker.

 > Lampirkan flowchart sederhana di sini. Flowchart menjelaskan secara garis besar: input-process-output

![flowchart](images/balancing.jpeg)

## Direktori `codes`:
1. `client_server.py` - *file untuk melakukan request ke server*
2. `broker_server.py` - *merupakan file yang berfungsi menerima request dari client kemudian di distribusikan ke worker *
3. `worker.py` - *merupakan file yang berfungsi untuk menerima request dari broker dan memprosesnya*

## Direktori `documentation`:
1. `panduan.pdf` - *merupakan file penjelasan dari sistem balancing prose dan flowchart cara kerja*

# Informasi anggota kelompok*
> tugas ini mandiri

Nama kelompok:

**Anggota**
1. Muhammad Rahulil  (25001905009)
