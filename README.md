# 1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
JAWABAN:
<img width="1920" height="1080" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/aff15eee-c9f0-4763-b4ba-466a197884f6" />
Penjelasan: Sudah dilakukan perubahan pada tag, dan hasilnya kode tidak error


# 2. Apa perbedaan dari tag (p) dengan tag (br), berikan penjelasannya!
JAWABAN:
# TAG (P)
<img width="1920" height="1080" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/3daf1117-85de-4265-b407-95c48bec0c7e" />
Penjelasan: Halaman HTML yang dibuat menampilkan struktur sederhana dengan memanfaatkan tag judul dan paragraf. Pada bagian atas digunakan tag (h1) sebagai judul utama, sehingga teks tampil besar dan jelas. Setelah itu, kalimat pengantar diletakkan di dalam tag (p), yang otomatis menampilkan teks dalam bentuk paragraf rapi. 
Selanjutnya, tag (h2) dipakai untuk membuat subjudul, diikuti paragraf panjang yang menjelaskan definisi dan fungsi HTML.
Penggunaan kombinasi (h1), (h2), dan (p) membantu menyusun isi halaman agar terstruktur dengan baik. Judul berfungsi memberi penekanan pada topik utama, subjudul menandai bagian penjelasan, sedangkan paragraf memisahkan teks sehingga lebih mudah dibaca dan dipahami.

# TAG (br)
<img width="1920" height="1080" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/80bdd786-dcdb-4767-9829-8eae4003c720" />
Penjelasan: Pada halaman HTML tersebut, terlihat bahwa peralihan baris teks menggunakan tag (br) alih-alih memanfaatkan tag paragraf (p). Tag (br) (break line) berfungsi untuk memberikan jeda baris atau memaksa teks turun ke baris berikutnya, tanpa membuat jarak antarblok seperti pada paragraf. Hal ini bisa dilihat pada bagian pengantar yang berisi perkenalan, di mana setiap potongan kalimat ditulis ke bawah dengan baris baru karena adanya sisipan <br>.
Perbedaan mendasarnya dengan (p) adalah, (p) menghasilkan sebuah blok teks yang memiliki spasi otomatis di atas dan bawah,
sehingga terlihat lebih rapi sebagai sebuah paragraf. Sedangkan (br) hanya memutus baris, sehingga teks tampak lebih rapat tanpa ada jarak tambahan. Karena itu, (br) biasanya dipakai untuk pemisah baris yang sifatnya singkat, misalnya dalam penulisan alamat, puisi, atau data yang memang butuh jeda baris, bukan untuk membuat paragraf panjang.
Dengan kata lain, penggunaan (br) dalam contoh ini menjadikan teks lebih padat dan berkesan “langsung turun ke baris berikutnya”, berbeda dengan (p) yang menampilkan teks dalam bentuk paragraf utuh.


# 3. Apa perbedaan atribut title dan alt pada tag (im)>, berikan penjelasannya!
JAWABAN:
<img width="1920" height="1080" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/3aaa7133-efdc-4594-a689-1f1f98508320" />
Penjelasannya: 
- alt → teks pengganti gambar (ditampilkan jika gambar gagal dimuat, penting untuk SEO & aksesibilitas).
- title → teks keterangan tambahan (muncul sebagai tooltip saat mouse diarahkan ke gambar).
Jadi bisa dibilang alt itu wajib dipakai untuk mendeskripsikan gambar, sedangkan title lebih bersifat opsional untuk memberi info tambahan.


# 4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
JAWABAN:
<img width="600" height="87" alt="Cuplikan layar 2025-09-22 204930" src="https://github.com/user-attachments/assets/1cb9fb75-c654-45e7-8f97-4f27d42208dd" />
<img width="1920" height="1080" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/b6d6ed94-a1cd-4ba0-a3ff-5b193b290279" />
Penjelasan:
Dalam tag (img), atribut width dan height digunakan untuk mengatur ukuran gambar di halaman web. Nah, supaya tampilan gambar tetap proporsional (tidak gepeng atau melebar aneh), sebaiknya cukup mengisi salah satu atribut saja, biasanya width.
Kenapa begitu?
1. Kalau kamu mengisi kedua atribut sekaligus dengan nilai yang tidak sesuai perbandingan asli gambar (aspect ratio), maka gambar bisa terlihat terdistorsi (entah jadi gepeng atau melebar).
2. Kalau kamu hanya mengisi satu atribut (misalnya width saja), maka browser otomatis akan menyesuaikan ukuran atribut lainnya agar rasio gambar tetap terjaga.
