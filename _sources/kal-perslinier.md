---
title: 'Penyelesaian Sistem Persamaan '

---

# Penyelesaian Sistem Persamaan Linier

Penyelesaian Sistem Persamaan Linier (SPL) adalah proses mencari nilai variabel yang memenuhi semua persamaan dalam sistem persamaan linier secara bersamaan. Sistem ini terdiri dari beberapa persamaan linier yang memiliki satu atau lebih variabel.


1. Jenis Penyelesaian SPL

Sistem persamaan linier bisa memiliki tiga kemungkinan solusi:

a. Sistem Konsisten dan Memiliki Satu Solusi (Tunggal)

- Garis atau bidang bertemu di satu titik.
- Sistem ini memiliki solusi unik.

b. Sistem Konsisten dan Memiliki Banyak Solusi (Tak Hingga Solusi)

- Garis atau bidang saling berhimpit.
- Sistem ini memiliki solusi tak terbatas.

c. Sistem Tidak Konsisten (Tidak Memiliki Solusi)
- Garis atau bidang saling sejajar tetapi tidak  bertemu.
- Sistem ini tidak memiliki solusi.




## Operasi Baris Elementer

(OBE) adalah operasi yang dilakukan pada baris suatu matriks untuk menyelesaikan sistem persamaan linear (SPL). OBE juga dapat digunakan untuk menentukan invers suatu matrik.

1. Contoh Penyelesaian Sistem Persamaan Linier dengan OBE

- Misalkan ada sistem persamaan linier:

\begin{array}{cc}
x+y+z=6\\
2_x+3_y+z=14\\
y+2_z=8\\
\end{array}


- Dalam bentuk matriks augmented:

\
\begin{bmatrix}
1 & 1 & 1&|6 \\
2 & 3 & 1&|14 \\
0 & 1 & 2&|8 \\
\end{bmatrix}




## Eliminasi Gaus

Eliminasi Gauss adalah metode dalam aljabar linier yang digunakan untuk menyelesaikan sistem persamaan linear. Metode ini dinamai untuk menghormati Carl Friedrich Gauss, seorang matematikawan terkenal

* contoh soal 1
selesaikan dengan eliminasi gaus 

$$
\begin{array}{cc}
x_1+2x_2+3x_3&=6\\
2x_1+4x_2+6x_3&=12\\
x_3+x_2&=2\\
\end{array}
$$

jawaban: 

\begin{bmatrix}
1 & 2 & 3 & | 6\\
2 & 4 & 6 & | 12\\
0 & 1 & 1 & | 2\\
\end{bmatrix}

\
$$
\begin{array}{cc}
R_2 \rightarrow R_2 \rightarrow 2R_1\\
\end{array}
$$

Sehingga:

\begin{bmatrix}
1 & 2 & 3 & | 6 \\
0 & 0 & 0 & | 0 \\
0 & 1 & 1 & | 2 \\
\end{bmatrix}

\
\begin{aligned}
x_1 + 2x_2 + 3x_3 &= 6 \\
x_2 + x_3 &= 2
\end{aligned}

\
$$
\begin{array}{cc}
x_2 = 2 - x_3\\
\end{array}
$$

Substitusikan ke persamaan pertama:

\
\begin{array}{cc}
x_1 + 2(2 - x_3) + 3x_3 = 6
\end{array}

\
\begin{array}{cc}
x_1 + 4 - 2x_3 + 3x_3 = 6
\end{array}

\
\begin{array}{cc}
x_1 + 4 + x_3 = 6
\end{array}

\
\begin{array}{cc}
x_1 = 2 - x_3
\end{array}

Kesimpulan:
\
$$
\begin{aligned}
x_1 &= 2 - x_3 \\
x_2 &= 2 - x_3 \\
x_3 &= x_3
\end{aligned}
$$

sistem ini tak hingga banyak solusi



* contoh soal 2

$$
\begin{array}{cc}
x_1+x_2+x_3=3\\
2x_1+x_3=5\\
x_1+2x_2=3\\
\end{array}
$$


jawaban:

\
$$
\begin{bmatrix}
1 & 1 & 1 & | 3 \\
2 & 0 & 1 & | 5 \\
1 & 2 & 0 & | 3 \\
\end{bmatrix}
$$

Gunakan Operasi:

\begin{array}{cc}
R_2 \rightarrow R_2 \rightarrow 2R_1
\end{array}

\begin{array}{cc}
R_3 \rightarrow R_3 \rightarrow R_1
\end{array}

Sehingga matriks berubah menjadi:

\
\begin{bmatrix}
1 & 1 & 1 & | 3 \\
0 & -2 & -1 & | -1 \\
0 & 1 & -1 & | 0
\end{bmatrix}

Selanjutnya, buat elemen utama di baris kedua menjadi 1 dengan membagi baris kedua dengan -2:

\begin{array}{cc}
R_2 \rightarrow \frac{R_2}{-2}
\end{array}

Hasilnya:

\
\begin{bmatrix}
1 & 1 & 1 & | 3 \\
0 & 1 & \frac{1}{2} & | \frac{1}{2} \\
0 & 1 & -1 & | 0
\end{bmatrix}

Kemudian eliminasi elemen di bawah elemen utama dengan:

\begin{array}{cc}
R_3 \rightarrow R_3 - R_2
\end{array}

Sehingga diperoleh:

\
\begin{bmatrix}
1 & 1 & 1 & | 3 \\
0 & 1 & \frac{1}{2} & | \frac{1}{2} \\
0 & 0 & -\frac{3}{2} & | -\frac{1}{2}
\end{bmatrix}

subtitusi balik:

Dari baris ketiga:

\begin{array}{cc}
-\frac{3}{2} x_3 = -\frac{1}{2}
\end{array}

\begin{array}{cc}
x_3 = \frac{1}{3}
\end{array}

Dari baris kedua:

\begin{array}{cc}
x_2 + \frac{1}{2} x_3 = \frac{1}{2}
\end{array}


\begin{array}{cc}
x_2 + \frac{1}{2} \times \frac{1}{3} = \frac{1}{2}
\end{array}

\begin{array}{cc}
x_2 + \frac{1}{6} = \frac{1}{2}
\end{array}

\begin{array}{cc}
x_2 = \frac{1}{2} - \frac{1}{6} = \frac{3}{6} - \frac{1}{6} = \frac{2}{6} = \frac{1}{3}
\end{array}

Dari baris pertama:

\begin{array}{cc}
x_1 + x_2 + x_3 = 3
\end{array}


$$
\begin{array}{cc}
x_1 = 3 - \frac{2}{3} = \frac{9}{3} - \frac{2}{3} = \frac{7}{3}
\end{array}
$$

Jadi, solusi dari sistem persamaan adalah:

\
\begin{aligned}
x_1 &= \frac{7}{3} \\
x_2 &= \frac{1}{3} \\
x_3 &= \frac{1}{3}
\end{aligned}


* contoh soal 3

$$
\begin{array}{cc}
2x_1+2x_2=4\\
x_1+x_2=2\\
\end{array}
$$

jawaban:


\begin{array}{cc}
x_1+x_2=2
\end{array}

kita bisa menyatakan x1 dalam bentuk x2:

\begin{array}{cc}
x_1=2-x_2
\end{array}

subtitusi ke persamaan pertama:

\begin{array}{cc}
2(2-x_2)+2x_2=4
\end{array}

Distrubikan:

\begin{array}{cc}
4-2x_2+2x_2=4
\end{array}

sederhanakan:

\begin{array}{cc}
4=4
\end{array}


* contoh soal 4

$$
\begin{array}{cc}
x_1+x_2=5\\
x_1+2x_3=6\\
\end{array}
$$

jawaban:

1. Nyatakan x1 dari persamaan pertama:
 
   \begin{array}{cc}
   x_1 = 5 - x_2
   \end{array}

2. Substitusikan ke persamaan kedua:
 
   \begin{array}{cc}
   (5 - x_2) + 2x_3 = 6
   \end{array}

3. Sederhanakan:
 
   \begin{array}{cc}
   5 - x_2 + 2x_3 = 6
   \end{array}

4. Susun ulang:

   \begin{array}{cc}
   -x_2 + 2x_3 = 1
   \end{array}

5. Nyatakan x2 dalam bentuk x3:

   \begin{array}{cc}
   x_2 = 2x_3 - 1
   \end{array}

6. Substitusikan kembali ke ekspresi x1:


   \begin{array}{cc}
   x_1 = 5 - (2x_3 - 1)
   \end{array}

7. Sederhanakan:
 
   \begin{array}{cc}
   x_1 = 6 - 2x_3
   \end{array}

Jadi, solusi umum untuk sistem ini adalah:

\begin{array}{cc}
x_1 = 6 - 2t, \quad x_2 = 2t - 1, \quad x_3 = t
\end{array}

dengan \( t \) sebagai parameter bebas.

