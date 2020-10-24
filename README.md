# Bahasa Pemrograman Rust

![Build Status](https://github.com/rust-lang/book/workflows/CI/badge.svg)

Repositori ini mengandung sumber dari buku "The Rust Programming Language".

[Buku ini tersedia dalam bentuk cetak dan digital dari No Starch Press][nostarch].

[nostarch]: https://nostarch.com/rust

Anda juga bisa membaca buku ini gratis secara daring. Silahkan cek buku yang tersedia dalam rilis [stable], [beta], atau [nightly] terbaru dari Rust. Harap diperhatikan bahwa isu pada versi tersebut bisa jadi telah diperbaiki pada repositori ini berhubung rilis tersebut tidak begitu sering diperbarui.

[stable]: https://doc.rust-lang.org/stable/book/
[beta]: https://doc.rust-lang.org/beta/book/
[nightly]: https://doc.rust-lang.org/nightly/book/

Silahkan lihat [rilis] tersebut untuk mengunduh kode dari semua daftar kode yang muncul pada buku ini.

[rilis]: https://github.com/rust-lang/book/releases

## Persyaratan

Untuk membuat buku ini dibutuhkan [mdBook], idealnya gunakan versi yang sama dengan yang digunakan rust-lang/rust pada [berkas ini][rust-mdbook]. Untuk mendapatkannya, jalankan:

```bash
$ cargo install mdbook --vers [version-num]
```

[mdBook]: https://github.com/rust-lang-nursery/mdBook
[rust-mdbook]: https://github.com/rust-lang/rust/blob/master/src/tools/rustbook/Cargo.toml

## Pembuatan

Untuk membuat buku ini, ketik:

```bash
$ mdbook build
```

Hasilnya akan muncul pada subdirektori `book`. Untuk melihatnya, bukalah menggunakan peramban anda.

_Firefox:_
```bash
$ firefox book/index.html                       # Linux
$ open -a "Firefox" book/index.html             # OS X
$ Start-Process "firefox.exe" .\book\index.html # Windows (PowerShell)
$ start firefox.exe .\book\index.html           # Windows (Cmd)
```

_Chrome:_
```bash
$ google-chrome book/index.html                 # Linux
$ open -a "Google Chrome" book/index.html       # OS X
$ Start-Process "chrome.exe" .\book\index.html  # Windows (PowerShell)
$ start chrome.exe .\book\index.html            # Windows (Cmd)
```

Untuk melakukan tes, ketik:

```bash
$ mdbook test
```

## Kontribusi

Kami sangat menghargai bantuan anda! Silahkan lihat [CONTRIBUTING.md][contrib] untuk memelajari tentang macam macam kontribusi yang kami butuhkan.

[contrib]: https://github.com/rust-lang/book/blob/master/CONTRIBUTING.md

### Penerjemahan

Kami sangat menghargai bantuan menerjemahkan buku ini! Silahkan periksa label [Translations] untuk bergabung bersama dalam proses penerjemahan. Buatlah isu baru untuk mulai mengerjakan penerjamahan bahasa baru! Kami menantikan [dukungan mdbook] untuk berbagai macam bahasa sebelum kami menggabungkan semuanya, namun anda bisa mulai kapanpun!

[Translations]: https://github.com/rust-lang/book/issues?q=is%3Aopen+is%3Aissue+label%3ATranslations
[dukungan mdbook]: https://github.com/rust-lang-nursery/mdBook/issues/5

## Pemeriksaan Ejaan Kata

Untuk memeriksa kesalahan pengejaan pada berkas, anda bisa menggunakan skrip `spellcheck.sh`. Dibutuhkan sebuah kamus kata baku yang disediakan di `dictionary.txt`. Jika skrip tersebut menghasilkan sebuah *false positive* (Misal, ketika menggunakan kata `BTreeMap` kemudian skrip menyatakan terdapat kesalahan pengejaan), anda perlu menambahkan ini pada `dictionary.txt` (Pastikan diurutkan dengan benar setelah menambahkan untuk konsistensi).