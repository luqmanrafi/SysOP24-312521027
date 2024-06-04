# Readers And Writers
Readers and Writers adalah masalah klasik sinkronisasi proses, ini berkaitan dengan kumpulan data seperti file yang dibagikan antara lebih dari satu proses pada satu waktu. Di antara berbagai proses ini, ada pula yang Pembaca - yang hanya dapat membaca kumpulan data; mereka tidak melakukan pembaruan apa pun, ada pula yang Penulis - dapat membaca dan menulis dalam kumpulan data.

Masalah pembaca-penulis digunakan untuk mengatur sinkronisasi antara berbagai proses pembaca dan penulis sehingga tidak ada masalah dengan kumpulan data, yaitu tidak terjadi ketidakkonsistenan.

Mari kita pahami dengan sebuah contoh - Jika dua atau lebih dari dua pembaca ingin mengakses file pada saat yang sama, tidak akan ada masalah. Namun, dalam situasi lain seperti ketika dua penulis atau satu pembaca dan satu penulis ingin mengakses file pada saat yang sama, mungkin ada beberapa masalah, maka tugasnya adalah merancang kode sedemikian rupa sehingga jika salah satu pembaca dapat membaca maka tidak ada penulis yang diperbolehkan memperbarui pada saat yang sama, demikian pula, jika salah satu penulis sedang menulis, tidak ada pembaca yang diperbolehkan membaca file pada saat itu dan jika salah satu penulis sedang memperbarui file, penulis lain tidak boleh membaca perbarui file pada titik waktu yang sama. Namun, beberapa pembaca dapat mengakses objek tersebut secara bersamaan.

![alt text](assets/read.png)

# Dining Philosopher problems
Dining Philospher adalah masalah sinkronisasi klasik yang mengatakan bahwa Lima filsuf duduk mengelilingi meja bundar dan tugas mereka adalah berpikir dan makan secara bergantian. Semangkuk mie diletakkan di tengah meja bersama lima sumpit untuk masing-masing filosof. Untuk makan, seorang filsuf membutuhkan sumpit kanan dan kiri. Seorang filsuf hanya bisa makan jika ada sumpit kiri dan kanan sang filsuf. Jika kedua sumpit kiri dan kanan sang filsuf tidak tersedia, maka sang filsuf meletakkan sumpitnya (kiri atau kanan) dan mulai berpikir lagi.

Filsuf makan mendemonstrasikan sejumlah besar masalah kontrol konkurensi sehingga ini merupakan masalah sinkronisasi klasik.

![alt text](assets/din.png)
