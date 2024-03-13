# Consume Data NodeJS

<p>Pada latihan ini, kita akan membuat 2 layanan REST API yang berbeda, kemudian menggabungkannya di satu layanan REST API. Layanan REST API yang akan kita buat adalah fitur order dan user terpisah di dua layanan dan menggabungkannya di satu layanan yang menampilkan data order dan user.</p>

## Cara kerja

- Install semua dependensi yang dibutuhkan `npm install`
- Jalankan file server.js = `npm run start`
- Jalankan file order-service.js = `npm run start:order`
- Jalankan file user-service.js = `npm run start:user`
- Kemudian akses url http://localhost:3000/{id}

> {id} yang dimaksud adalah data yang tertampung dalam array pada file order dan user, contoh = http://localhost:3000/1
