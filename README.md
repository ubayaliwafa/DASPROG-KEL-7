LAPORAN PROYEK
KALKULATOR SEDERHANA ELEKTRO & KONVERSI BILANGAN

NAMA : UBAY ALI WAFA
NRP : 5022231244






Bahasa C

1. Pendahuluan

Perkembangan teknologi di bidang elektro dan sistem digital menuntut kemampuan dalam melakukan perhitungan dasar secara cepat dan akurat. Oleh karena itu, dibutuhkan sebuah program sederhana yang dapat membantu perhitungan kelistrikan serta konversi bilangan digital.

Proyek ini dibuat berupa program berbasis bahasa C yang menyediakan beberapa fitur perhitungan dasar elektro dan konversi bilangan dengan tampilan menu interaktif berbasis teks (console).

2. Tujuan Program

Tujuan dari pembuatan program ini adalah:

Membantu melakukan perhitungan dasar kelistrikan.

Memahami penerapan bahasa C dalam program berbasis menu.

Melatih penggunaan fungsi, perulangan, dan percabangan.

Membantu proses pembelajaran sistem bilangan digital.

3. Ruang Lingkup Program

Program ini memiliki ruang lingkup sebagai berikut:

Perhitungan Hukum Ohm

Perhitungan daya listrik

Perhitungan hambatan resistor seri dan paralel

Konversi bilangan desimal, biner, oktal, dan heksadesimal

Antarmuka berbasis teks (console)

4. Dasar Teori
   
4.1 Hukum Ohm

Hukum Ohm menyatakan hubungan antara tegangan, arus, dan hambatan:

𝑉 = 𝐼 × 𝑅

4.2 Daya Listrik

Daya listrik dapat dihitung menggunakan rumus:

𝑃 = 𝑉 × 𝐼

4.3 Resistor Seri

Hambatan total rangkaian seri:

𝑅𝑡𝑜𝑡𝑎𝑙=𝑅1+𝑅2+⋯+𝑅𝑛

Rtotal=R1+R2+⋯+Rn
	​
4.4 Resistor Paralel

Hambatan total rangkaian paralel:

1𝑅𝑡𝑜𝑡𝑎𝑙=1𝑅1+1𝑅2+⋯+1𝑅𝑛Rtotal​

4.5 Sistem Bilangan

Program mendukung konversi antar sistem bilangan:

Desimal

Biner

Oktal

Heksadesimal

5. Perancangan Program

5.1 Struktur Program

Program dirancang menggunakan beberapa fungsi agar lebih terstruktur, antara lain:

displayMenu() → Menampilkan menu utama

clearScreen() → Membersihkan layar

ohmLaw() → Menghitung Hukum Ohm

powerCalc() → Menghitung daya listrik

seriesResistor() → Resistor seri

parallelResistor() → Resistor paralel

decToOthers() → Konversi dari desimal

binToDec(), octToDec(), hexToDec() → Konversi ke desimal

main() → Mengatur alur program

6. Implementasi Program

Program dibuat menggunakan bahasa C dan dijalankan melalui terminal/console.
Menu utama ditampilkan secara berulang menggunakan perulangan while, sehingga pengguna dapat memilih fitur yang diinginkan hingga memilih menu keluar.

7. Cara Menjalankan Program
7.1 Kompilasi Program
gcc program.c -o program

7.2 Menjalankan Program
./program

8. Hasil dan Pembahasan

Program berhasil:

Menghitung nilai tegangan, daya, dan hambatan dengan benar

Melakukan konversi sistem bilangan dengan akurat

Menampilkan menu interaktif yang mudah digunakan

Program ini dapat digunakan sebagai alat bantu praktikum elektro dan media pembelajaran dasar bahasa C.

9. Kelebihan dan Kekurangan
9.1 Kelebihan

Menu sederhana dan mudah digunakan

Struktur program rapi menggunakan fungsi

Cocok untuk pembelajaran dasar elektro dan pemrograman

9.2 Kekurangan

Antarmuka masih berbasis teks

Hanya berjalan optimal di sistem Windows

Belum mendukung validasi input secara menyeluruh

10. Kesimpulan

Berdasarkan hasil pengujian, program kalkulator elektro dan konversi bilangan ini dapat berjalan dengan baik sesuai dengan tujuan yang diharapkan. Program ini membantu memahami konsep dasar kelistrikan serta penerapan bahasa C dalam pemrograman terstruktur.

11. Saran Pengembangan

Pengembangan selanjutnya yang dapat dilakukan:

Menambahkan validasi input

Mengembangkan antarmuka berbasis GUI

Menambahkan fitur perhitungan kelistrikan lainnya

12. Penutup

Demikian laporan proyek ini dibuat sebagai dokumentasi program dan bahan pembelajaran. Diharapkan program ini dapat bermanfaat bagi pengguna dan pengembang selanjutnya.
