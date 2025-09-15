# Posttest2-PBO-JadwalElektronikservices
# sistem manajemen jadwal services alat elektronik

# penjelasan package
<img width="423" height="224" alt="image" src="https://github.com/user-attachments/assets/372a8e4d-de3b-4886-93b9-a11aa55252a2" />

project JadwalElektronikServices menggunakan tiga package utama sesuai konsep MVC. package model berisi class jadwal yang menyimpan struktur data jadwal service elektronik, termasuk atribut id, namaService, dan tanggal, beserta constructor, getter/setter, dan toString() untuk menampilkan data. package service berisi class jadwalservices yang menangani logika CRUD (tambah, lihat, hapus, update) dan pencarian jadwal berdasarkan ID, sehingga mengelola data dari model tanpa menampilkan menu. Sedangkan package main berisi class MainApp yang menjadi controller, menampilkan menu interaktif kepada user, menerima input melalui Scanner, dan memanggil method di jadwalservices untuk memproses data. Dengan struktur ini, project menjadi modular, rapi, dan memisahkan antara representasi data, logika pengolahan, dan interaksi dengan 

# penjelasan alur program
<img width="440" height="705" alt="image" src="https://github.com/user-attachments/assets/f4f14aa8-968b-4c50-82a9-f9aced0b0d9e" />

alur program JadwalElektronikServices dimulai dari class MainApp di package main, yang berfungsi sebagai controller. Program menampilkan menu interaktif untuk menambah, melihat, menghapus, mengupdate, atau mencari jadwal, serta keluar dari program. Input user diterima melalui Scanner dan diteruskan ke class jadwalservices di package service untuk memproses logika CRUD dan pencarian. Data jadwal disimpan sebagai objek jadwal di package model. Setelah operasi selesai, hasil dikembalikan ke MainApp untuk ditampilkan. Program terus berjalan hingga user memilih keluar. Struktur ini mengikuti prinsip MVC, memisahkan data, logika, dan tampilan sehingga lebih modular dan mudah dikembangkan.
