# Binary Search

## Deskripsi

Ingin bermain game? Saat Anda menggunakan lebih banyak shell, Anda mungkin tertarik dengan cara kerjanya! Pencarian biner adalah algoritma klasik yang digunakan untuk menemukan item dengan cepat dalam daftar yang diurutkan. Dapatkah Anda menemukan benderanya? Anda akan mendapatkan 1000 kemungkinan dan hanya 10 tebakan. Keamanan siber sering kali memiliki banyak sekali data yang harus ditelusuri - mulai dari log, laporan kerentanan, dan forensik. Berlatih dasar-dasarnya secara manual mungkin akan membantu Anda di masa depan ketika Anda harus menulis alat Anda sendiri! Anda bisa mengunduh file tantangannya di sini:

[challenge.zip](https://artifacts.picoctf.net/c_atlas/17/challenge.zip)

ssh -p 64479 ctf-player@atlas.picoctf.net Menggunakan kata sandi f3b61b38. Terima sidik jari dengan ya, dan ls setelah tersambung untuk memulai. Ingat, di dalam shell, kata sandi disembunyikan!

**note**: port dan password setiap mesin berbeda

## Langkah - langkah

#### Download file

gunakan perintah `wget`

- `wget link_address`

#### Unzip file

gunakan perintah `unzip`

- `unzip file_name`

Setelah unzip akan terdapat direktori `home/ctf-player/drop-in/guessing_game.sh`.

Jika menganalisa file `guessing_game.sh` kita hanya dapat menebak angka sebanyak 10 kali, dan angka setiap mesin dijalankan akan random.

masuk ke server `ssh -p 64479 ctf-player@atlas.picoctf.net`. gunakan sandi `f3b61b38`. lakukan percobaan sampai benar 😀.

![binary-search]()
