# pemrograman_mobile_uts

 NIM:312210381
 
 NAMA:Muhammad Dzaki Abiyyu
 
 KELAS: TI.22.A4

 # Deret Fibonaci 

Deret Fibonacci adalah suatu deret bilangan yang dimulai dari 0 dan 1, dan setiap suku berikutnya merupakan hasil penjumlahan dari dua suku sebelumnya. Secara matematis, deret Fibonacci dapat dinyatakan dengan rumus rekursif sebagai berikut:


F(n)=F(n−1)+F(n−2)

dengan kondisi awal:

F(0) = 0,
F(1) = 1,
Dengan menggunakan rumus ini, kita dapat menghasilkan deret Fibonacci sebagai berikut:

0
,
1
,
1
,
2
,
3
,
5
,
8
,
13
,
21
,
34
,
…
0,1,1,2,3,5,8,13,21,34,…

Artinya, setiap angka dalam deret tersebut merupakan hasil penjumlahan dari dua angka sebelumnya. Deret Fibonacci memiliki banyak aplikasi dalam matematika, ilmu komputer, dan berbagai bidang lainnya.

### 1.  Rekursi
`def fibonacci_recursive(n):
    if n <= 1:
        return n
    else:
        return fibonacci_recursive(n-1) + fibonacci_recursive(n-2)`



