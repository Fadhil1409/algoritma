Berikut adalah analisis Big O (Worst-case) dan *Big Θ* (Average-case) untuk kedua algoritma:

1. Bubble Sort


Kompleksitas Waktu:
- Worst-case (Big O):  
  - Dalam skenario terburuk, array diurutkan terbalik sehingga setiap elemen harus ditukar.  
  - Loop luar berjalan (n) kali, dan loop dalam mendekati (n) iterasi rata-rata.  
  - Kompleksitas total:  
  
    O(n^2)

- Average-case (Big Θ):  
  - Secara rata-rata, setiap elemen akan dipindahkan setengah jumlah maksimum perpindahan.
  - Karena struktur loop tidak berubah, jumlah total operasi tetap dalam orde kuadrat:  
    \[
    \Theta(n^2)
    \]

 *2. Merge Sort

*Kompleksitas Waktu:*
- *Worst-case (Big O):*  
  - Setiap pembagian array membutuhkan waktu logaritmik karena array dibagi menjadi dua bagian ((O(log n))).
  - Proses penggabungan memerlukan waktu linear pada setiap level ((O(n))).  
  - Total kompleksitas:  
    \[
    O(n \log n)
    \]
- *Average-case (Big Θ):*  
  - Sama seperti kasus terburuk karena struktur rekursif algoritma selalu membagi dan menggabungkan array dengan pola yang sama.  
    
    \Theta(n \log n)
    

