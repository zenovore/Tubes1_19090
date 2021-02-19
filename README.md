# Tubes1_19090
Dibuat untuk memenuhi Tugas besar 1 Mata Kuliah IF2211 Strategi Algoritma .

## Algoritma Greedy yang Diimplementasikan
> Kami mendekomposisi permainan Worms menjadi 3 bagian yaitu menyerang, bergerak, dan bertahan yang memiliki algoritma greedy nya masing-masing. Berikut adalah penjelasan untuk masing-masing algoritma.

### Algoritma Greedy Menyerang
> Algoritma greedy menyerang dilakukan dengan cara mengincar cacing musuh yang memiliki kemungkinan untuk menghasilkan damage yang palin tinggi terlebih dahulu, hal ini dilakukan dengan harapan tim kami akan semakin diuntungkan di akhir permainan ketika cacing yang berbahaya sudah mati.
### Algoritma Greedy Bergerak
> Algoritma greedy bergerak dilakukan dengan memanfaatkan algoritma Dijkstra dan memiliki tujuan untuk mencari rute dengan cost yang paling minimal pada map.
### Algoritma Greedy Bertahan
> Algoritma greedy bertahan dilakukan dengan cara melakukan pengecekan pada 1 cell sekitar suatu cacing untuk mencari cell mana yang paling optimal sebagai target perpindahan cacing yaitu cell yang tidak bisa ditembak musuh dan bukan lava.

## Requirements
Java 8

IntelliJ IDEA
## Cara Menjalankan Program
Windows:
1. Install / build Bot.java menggunakan IntelliJ IDEA
2. Buka directory bin
3. Jalankan run.bat

Linux:
1. Buka directory bin
2. make run
```sh
$ make run
```

## Author
* 13519090 Alexander
* 13519116 Jeane Mikha Erwansyah
* 13519131 Hera Shafira

## Referensi
[Entellect Challenge 2019](https://github.com/EntelectChallenge/2019-Worms)

