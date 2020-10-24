# Pedoman Penulisan

## Prosa

* Gunakan huruf kapital di awal kata untuk judul dari bab/bagian, contoh: `## Menghasilkan Sebuah Angka Rahasia` lebih baik daripada `## Menghasilkan sebuah angka rahasia`.
* Gunakan huruf miring bukan tanda petik untuk menyebutkan sebuah istilah, contoh: `merupakan sebuah
  *associated function* dari` lebih baik daripada `merupakan sebuah
  ‘associated function‘ dari`.
* Ketika membahas tentang sebuah *method* pada prosa, JANGAN menambahkan tanda kurung, contoh: `read_line` lebih baik daripada `read_line()`.
* *Hard wrap* pada 80 karakter.
* Hindari mencampur kode dengan bukan kode dalam satu kata. Contoh: ``Ingat ketika kita menulis `use std::io`?`` lebih baik daripada ``Ingat ketika kita menggunakan `use`d`std::io`?``

## Kode

* Tambahkan nama berkas sebelum blok *markdown* untuk memperjelas berkas mana yang dibahas bila memungkinkan.
* Ketika membuat perubahan pada kode, perjelas bagian mana yang berubah dan mana yang tidak... masih belum tentu bagaimana melakukannya.
* Pisahkan baris yang panjang untuk menyesuaikan panjangnya di bawah 80 karakter bila memungkinkan.
* Gunakan `bash` *syntax highlighting* ketika membuat blok kode hasil dari *command line*

## Tautan

Setelah semua skrip selesai:

* Jika sebuah tautan tidak perlu dicetak, tandai untuk diabaikan
  * Ini mencakup semua tautan "Bab XX" dalam buku, yang mana harusnya tautan tersebut untuk versi HTML.
* Buat tautan dalam buku dan tautan *stdlib API doc* relatif agar dapat berfungsi baik ketika buku tersebut dibaca secara luring maupun pada docs.rust-lang.org
* Gunakan tautan *markdown* dan perhatikan bahwa tautan tersebut akan berubah menjadi `teks pada *url*` saat dicetak, jadi gunakan kata yang mudah dibaca pada format tersebut.