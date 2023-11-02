# Klontong, the mobile project.

Sebuah toko klontong ingin masuk ke abad 21, mereka ingin menjual barang mereka online.

### Details

Secara basic:

> Sebagai anak owner toko klontong, saya butuh mengatur barang yang kami jual di sebuah table.

Dari perspective engineer, anggaplah ini hanya sebuah CRUD.

Temen kerja backend-mu akan siapkan RESTful API, namun mereka telat.
Tetapi kamu harus tetap mendemokan fitur-fitur selama API tersebut masih di bangun.
Tim kamu memutuskan bahwa API-nya akan di mock-up dulu. Sebagai mobile developer yang sangat jago,
ini menjadi tanggung jawab kamu.

Ini adalah stack mobile yang kamu **_harus_** gunakan untuk proyek ini:

- Flutter
- Bloc/Provider/GetX/Cubit

_Hint_: Ada backend CRUD otomatis online: <br/>
https://crudcrud.com/

### More technical details

Seluruh tim telah setuju dengan beberapa spek dan limitasi teknikal:

- Semua payload untuk request dan response adalah JSON.
- Ada skema data.
- Ada data sekitar 100 produk yang butuh di manage, gunakan teknik paginasi.
- Halaman-halaman yang ditetapkan:
  - List semua produk dengan fitur search dan paginasi
  - Detil produk
  - Tambah produk

Contoh skema:

```json
{
  "id": 86,
  "CategoryId": 14,
  "categoryName": "Cemilan",
  "sku": "MHZVTK",
  "name": "Ciki ciki",
  "description": "Ciki ciki yang super enak, hanya di toko klontong kami",
  "weight": 500,
  "width": 5,
  "length": 5,
  "height": 5,
  "image": "https://cf.shopee.co.id/file/7cb930d1bd183a435f4fb3e5cc4a896b",
  "harga": 30000
}
```

Jangan lupa, tim kamu bersifat internasional, jadi kerjakan
sebaik mungkin menggunakan bahasa Inggris.
(Walaupun iya sih, test ini ditulis menggukan bahasa Indonesia, tapi...)

### Extra features

Tim kamu tidak ada yang mengharapkannya. Tetapi it will be nice to see:

- State persistence, jika dibutuhkan save token (guna authentikasi), tentunya butuh di save di suatu tempat yang secure dong.
- Error reporting, kadang kita belum tau ada masalah apa di hp tipe apa kan ya? Bagaimana cara kita tau data ini?
- TDD, untuk menambah keyakinan anda bahwa semua code yang anda tulis telah melewati beberapa test
- Menerapkan SOLID Principle

KISS (Keep It Stupid Simple) - Jangan lupa target audience-nya kemungkinan gaptek.

### What we care about

Gunakan library apapun yang kamu biasa gunakan jika ini aplikasi production nyata.
Code design dan cleanliness lebih penting dibanding pemilihan library yang "benar".
Selalu strive to use best practices!

### Important!!
Jika kamu ada menggunakan environment variables, jangan lupa untuk share itu dengan kami beserta dengan credentials apapun yang mungkin kami butuhkan.

### Closing

Jangan lupa set github reponya ke publik, dan share dengan kami.

Be cool and happy coding!
