# SiberMu-sturktur-data-tugas-14-b
Tugas Praktek 14 - Array Multi Dimensi

Repositori ini berisi solusi dari Tugas Praktek 14 mengenai Struktur Data dengan topik **Array Multi Dimensi**. Program ini ditulis menggunakan bahasa pemrograman C.

## Deskripsi Program
Program ini mendemonstrasikan penggunaan array 3 dimensi di dalam bahasa C untuk menyimpan data bertipe string (karakter). Kasus yang diselesaikan adalah menampilkan daftar tim sepak bola dalam format **Liga Champions** yang dibagi ke dalam beberapa grup (Grup A hingga Grup E).

Data tim disimpan dalam sebuah array berukuran `[5][4][22]` yang berarti:
- `5`: Mewakili jumlah grup (Grup A, B, C, D, E)
- `4`: Mewakili jumlah tim di dalam setiap grup
- `22`: Menentukan panjang maksimal karakter untuk setiap nama tim

## Penyesuaian Kode
Program ini diadaptasi dari screenshot tugas awal. Beberapa penyesuaian yang telah dilakukan agar program dapat di-compile sesuai dengan standar bahasa C modern dan mendukung lingkungan Linux:
- Ditambahkan deklarasi variabel iterasi `int i, s;` sebelum proses pengulangan.
- Fungsi utama ditulis menggunakan penulisan standar `int main()` dengan nilai kembali `return 0;`.
- Pustaka `#include <conio.h>` dan fungsi `getch()` dihilangkan karena spesifik untuk sistem operasi Windows/DOS.

## Cara Kompilasi dan Menjalankan Program (Linux)

Anda dapat melakukan kompilasi program ini dengan GCC (GNU Compiler Collection). Jalankan perintah berikut di terminal:

```bash
# Melakukan kompilasi file C
gcc main.c -o main

# Menjalankan program hasil kompilasi
./main
```

## Hasil Keluaran (Output) Program
Jika dijalankan, program akan menghasilkan *output* sebagai berikut:

```text
Liga Champions : 

Grup A 
       1. AC Milan 
       2. Barcelona 
       3. Porto 
       4. Monaco 

Grup B 
       1. Liverpool 
       2. Real Madrid 
       3. CSK Moskow 
       4. PSG 

Grup C 
       1. Inter Milan 
       2. Arsenal 
       3. Atletico Madrid 
       4. Ajax 

Grup D 
       1. AS Roma 
       2. Manchester United 
       3. Dortmund 
       4. Valencia 

Grup E 
       1. Manchester City 
       2. Bayern Munich 
       3. Napoli 
       4. Vilareal 
```
