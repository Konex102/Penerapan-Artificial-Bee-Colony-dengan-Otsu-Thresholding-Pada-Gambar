Anggota Kelompok 4 :  
Fathia Feriztha Saifuddin  
Maulana Zacky Alghazari  
Bhisma Pradipta Putra  
Jordan Oktovianus Munthe

# Penerapan Artificial Bee Colony dengan Otsu Thresholding
## Pembuatan Fungsi Threshold
  Dalam melakukan proses threshold pada sebuah gambar dengan menggunakan artificial bee colony, dilakukan definisi untuk membuat sebuah fungsi threshold yang akan digunakan dimana dalam kondisi ini menggunakan Otsu Thresholding.

## Pembuatan Fungsi Kriteria Otsu dan Best Threshold
Setelah membuat definisi fungsi threshold, selanjutnya adalah membuat fungsi untuk membuat sebuah kriteria Otsu yang akan digunakan serta Best Threshold guna mencari nilai threshold pada sebuah gambar agar memiliki hasil yang baik. Pada fungsi untuk membuat kriteria otsu, digunakan sebuah persamaan sebagai berikut

![0__tkZIA-qvHXQfujh](https://github.com/Konex102/Penerapan-Artificial-Bee-Colony-dengan-Otsu-Thresholding-Pada-Gambar/assets/90701299/35e062b4-04d3-48d7-a7ea-fbb9d8e6a7a2)

Pada rumus tersebut terdapat dua nilai probabilitas yang didapatkan yaitu W0(k) yang merupakan probabilitas kelas latar belakang dan W1(k) merupakan probabilitas objek pada gambar tersebut. Selain terdapat nilai varians yang digunakan yaitu Oo^2k merupakan varians latar belakang dan O1^2k merupakan varians kelas kedua.

## Artificial Bee Colony dalam threshold
Dalam penggunaan ABC (Artificial Bee Colony) terdapat beberapa aktifitas yang dilakukan yaitu  inisialiasi populasi yang dimana dalam fungsi ini, maksimum bees yang digunakan sebanyak 20 dan iterasi maksimumnya sebesar 100. Dalam fungsi ini, terdapat pembagian kerja lebah yaitu _Employed Bees_, _Onlooker Bees_ dan _Scout bees.
