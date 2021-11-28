# labpy01
## Latihan 1

<p> Program Sederhana Menampilkan Blangan Terbesar </p>
  
  ![1](https://user-images.githubusercontent.com/92736847/141682724-16e69112-8f15-4137-8d0d-e5e190307928.png)
  
  ![2](https://user-images.githubusercontent.com/92736847/141682745-892e770f-3b51-4656-aff9-e62446444648.png)
  
Penjelasan :
  <p> 1. Buatlah integer untuk menginput bilangan bulat untuk di proses dan dimasukan ke variabel maks </p>

  ```bash
  a = int(input("Masukan Nilai 1 : "))
  b = int(input("Masukan Nilai 2 : "))
  ```
  Proses : 
     <p> 2. jika (if) bilangan a lebih besar dari biangan b maka bilangan a lebih besar </p>

  ```bash
  if a > b:
      makx = a

  ```
     3. jika (if) bilangan b lebih besar dari bilangan a maka bilangan b lebih besar 

  ```bash
  else:
      makx = b
  ```
     <p> 4. Untuk menampilkan hasil </p>

  ```bash
  print ("Bilangan terbesar Adalah : ",makx)
  ```

### Latihan 2

  <p> Program Menampilkan Sebuah Bilangan Dari Bilangan Terkecil ke Bilangan Terbesar </p>
  
  ![3](https://user-images.githubusercontent.com/92736847/141683621-3ec23e41-c656-4e77-84ee-19bfcac2618a.png)
  ![4](https://user-images.githubusercontent.com/92736847/141683628-63704876-df3d-4e03-b81a-aa3edb7c4840.png)
  
 <p> Penjelasan : </p>
   <p> 1. Untuk menginput lima buah bilangan yang akan dimasukan ke list variabel </p>
   
```bash
bilangan = []
for i in range(1,6):
    bilangan.append(int(input("Masukan Bilangan : ")))
```

  <p>  2. Data akan diproses menggunakan metode sort. yaitu metode untuk mengurutkan data, baik itu dari nilai terkecil ataupun terbesar. </p>

```bash
bilangan.sort()
```
   <p> 3. Untuk Menampilkan Data </p>

```bash
print("Urutan Bilangan",bilangan)
```

## Latihan 3
<p> Program Perulangan Bertingkat (Nested for) </p>

  ![5](https://user-images.githubusercontent.com/92736847/141684065-da88b286-5e0d-4b8e-b1d3-5b33b9514fd6.png)
  ![6](https://user-images.githubusercontent.com/92736847/141684071-2952d858-b12b-44a4-881f-bccfdc75e371.png)

<p> Penjelasan :
Note : i (Baris), j (Kolom) </p>
  <p>  1. Untuk melakukan perulangan baris dan kolom dengan nilai 10, menggunakan nested for </p>

```bash
for i in range (10):
    for j in range (10):
        
```
  <p>  2. Untuk hasil dari perulangan </p>

```bash
print ('%3d'%(i+j), end = '')
    print()
```

## Latiham 4
  
  <p> Program Menampilkan N Bilangan Acak yang Lebih Kecil dari 0.5 </p>
  
  ![1](https://user-images.githubusercontent.com/92736847/141684392-0992daff-c3dd-49ce-997e-ec5482b10eb9.png)
  ![2](https://user-images.githubusercontent.com/92736847/141684430-39b77b8f-4e88-4b6b-9468-cd8dc22217f7.png)

Penjelasan :
   
   <p> 1. Import Module Bilangan Random </p>

```bash
from random import random
``` 
   <p> 2. Untuk menginput nilai yang ingin dikonversikan kedalam bilangan bulat (Integer) yang akan di masukan kedalam variabel a </p>

```bash
a = int(input("Masukan Bilangan : "))
```
  <p>  3. Untuk pengulangan range yang diinputkan oleh variable a </p>

```bash
while a==a:
    break
for i in range(a):
    bil = random()%0.5
```
  <p>  4. Untuk Menampilkan bilangan a </p>

```bash
 print ("Perulangan ke- :", bil)
 print ("Selesai")
```
