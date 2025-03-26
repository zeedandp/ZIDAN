---
title: sistem persamaan linier
---

# SISTEM PERSAMAAN LINEAR
## PENGERTIAN
Kumpulan persamaan linear yang terdiri dari beberapa variabel. Sistem persamaan linear merupakan salah satu materi dalam ilmu matematika.

Sistem persamaan linear bisa diartikan sebagai suatu persamaan aljabar. Di mana persamaan linear sendiri memiliki karakteristik pada setiap sukunya mengandung konstanta atau perkalian konstanta dengan variabel tunggal.

## SOLUSI SISTEM PERSAMAAN LINIER
### METODE ELIMINASI
Metode eliminasi adalah salah satu metode yang digunakan untuk menyelesaikan soal persamaan linear dua atau tiga variabel. Di mana metode eliminasi secara garis besar akan menghapus atau menghilangkan satu variabel dalam persamaan tersebut.

#### ELIMINASI GAUSS
Sistem persamaan linear yang diubah menjadi bentuk matriks, matriks tersebut lalu diubah ke bentuk Eselon Baris melalui Operasi Baris Elementer. Kemudian sistem diselesaikan dengan substitusi balik.

#### MEMBUAT PENJELASAN SOLUSI ATAU PENYELESAIAN PERSAMAAN 3 VARIABEL DENGAN MENGGUNAKAN ELIMINASI GAUSS SERTA MENAMPILKAN SOLUSINYA SECARA GRAFIS MENGGUNAKAN GEOGEBRA.

Selesaikan sistem persamaan linier berikut:

$$\begin{cases} x + y + z = 6 \\ 2x + 2y + 3z = 14 \\ 3x + 4y + 2z = 13 \end{cases}$$

Berikut adalah langkah-langkah menyelesaikan sistem persamaan linear di atas menggunakan metode eliminasi Gauss.

1. **Langkah pertama**

   Hasil Matriksnya:

   $$\begin{bmatrix} 1 & 1 & 1 & | 6 \\ 2 & 2 & 3 & | 14 \\ 3 & 4 & 2 & | 13 \end{bmatrix}$$

2. **Langkah kedua**
   - Jadikan elemen pivot pertama (baris 1, kolom 1) bernilai 1.
   - Jika sudah bernilai 1, tidak perlu diubah.
   - Nol-kan elemen di bawah elemen pivot pertama.

   $$ R_2 \to R_2 - 2R_1 $$

   Hasil matriksnya:

   $$\begin{bmatrix} 1 & 1 & 1 & | 6 \\ 0 & 0 & 1 & | 2 \\ 3 & 4 & 2 & | 13 \end{bmatrix}$$

   $$ R_3 \to R_3 - 3R_1 $$

   Hasil matriksnya:

   $$\begin{bmatrix} 1 & 1 & 1 & | 6 \\ 0 & 0 & 1 & | 2 \\ 0 & 1 & -1 & | -5 \end{bmatrix}$$

   - Jadikan elemen pivot kedua (baris 2, kolom 2) bernilai 1:

   $$ R_2 \to R_2 + R_3 $$

   Hasil matriksnya:

   $$\begin{bmatrix} 1 & 1 & 1 & | 6 \\ 0 & 1 & 0 & | -3 \\ 0 & 1 & -1 & | -5 \end{bmatrix}$$

   - Nol-kan elemen di bawah elemen pivot kedua:

   $$ R_3 \to R_3 - R_2 $$

   Hasil matriksnya:

   $$\begin{bmatrix} 1 & 1 & 1 & | 6 \\ 0 & 1 & 0 & | -3 \\ 0 & 0 & -1 & | -2 \end{bmatrix}$$

   - Jadikan elemen pivot ketiga (baris 3, kolom 3) bernilai 1:

   $$ R_3 \to R_3 \cdot (-1) $$

   Hasil matriksnya:

   $$\begin{bmatrix} 1 & 1 & 1 & | 6 \\ 0 & 1 & 0 & | -3 \\ 0 & 0 & 1 & | 2 \end{bmatrix}$$

3. **Langkah ketiga: substitusi balik**
   - Dari baris terakhir:

     $$ z = 2 $$

   - Substitusi \( z \) ke baris kedua:

     $$ y + z = -3 $$
     $$ y + 2 = -3 $$
     $$ y = -3 - 2 $$
     $$ y = -5 $$

   - Substitusi \( y \) dan \( z \) ke baris pertama:

     $$ x + y + z = 6 $$
     $$ x + (-5) + 2 = 6 $$
     $$ x - 5 + 2 = 6 $$
     $$ x - 3 = 6 $$
     $$ x = 6 + 3 $$
     $$ x = 9 $$

   - **Solusi akhir:**

     $$ x = 9, \quad y = -5, \quad z = 2 $$

  ![Screenshot 2025-03-03 204248](https://hackmd.io/_uploads/HkgfQVXoyl.png)

  [https://www.geogebra.org/classic/bt2sr3ar](https://)

