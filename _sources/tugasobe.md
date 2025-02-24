## Penyelesaian Sistem Persamaan Linier
## Operasi Baris Elementer


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
0 & 1 & 1 & | 2
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
1 & 2 & 0 & | 3
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

\bagin{array}{cc}
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
x_1 = 3 - \frac{2}{3} = \frac{9}{3} - \frac{2}{3} = \frac{7}{3
\end{array}
$$




* contoh soal 3

$$
\begin{array}{cc}
2x_1+2x_2=4\\
x_1+x_2=2\\
\end{array}
$$

* contoh soal 4

$$
\begin{array}{cc}
x_1+x_2=5\\
x_1+2x_3=6\\
\end{array}
$$