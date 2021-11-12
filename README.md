# Praktikum labspy02 & labspy03

# labspy02
## Algoritma untuk menentukan nilai terbesar dari 3 buah bilangan

# Flowchart

Berikut flowchart untuk menentukan nilai terbesar dari 3 buah bilangan


![Flowchart](https://user-images.githubusercontent.com/92704969/141128430-cee9133c-c4f6-4418-9049-143402568d4b.png)


# Menggunakan statement if untuk mencari nilai terbesar dari 3 bilangan

#### Untuk a di inisialkan sebagai bilangan pertama, b untuk bilangan kedua, c untuk bilangan ketiga

#### Dengan cara statement if untuk a sebagai bilangan pertama, elif untuk b bilangan kedua, dan else untuk c bilangan ketiga, berikut gambar program dan tulisan programnya


![Praktikum2](https://user-images.githubusercontent.com/92704969/141128460-8472dfea-517c-4810-b44b-7a59b0e4b9a2.png)


#### Untuk hasil ketika program dijalankan, bilangan pertama yang terbesar

![Kondisi1](https://user-images.githubusercontent.com/92704969/141128443-40b22937-cc7a-459d-be03-cb6886db872d.png)

#### Untuk bilangan kedua yang terbesar ketika program dijalankan

![Kondisi2](https://user-images.githubusercontent.com/92704969/141128453-26a48783-ac26-41b1-9194-e5ad4cc475ed.png)

#### Dan untuk bilangan ketiga yang terbesar ketika program dijalankan

![Kondisi3](https://user-images.githubusercontent.com/92704969/141128455-4ed28de1-dda5-4d51-9bdb-df2cc6203c26.png)

# labspy03

# Latihan 1 

## Program Untuk Menampilkan n Bilangan Acak Yang Lebih Kecil Dari 0.5

### Flowchart Program
#### berikut flowchart dari program latihan 1, untuk menampilkan n bilangan acak yang lebih kecil dari 0.5

![flowchart_latihan1](https://user-images.githubusercontent.com/92704969/141401219-ed9b1ad4-e83a-4622-8179-a311b8938e0c.png)

### Penjelasan alur program
1. print("Tampilkan n bilangan acak yang lebih kecil dari 0.5") - adalah perintah untuk menampilkan judulnya.

2. jumlah = int(input("Masukkan jumlah n: ")) - adalah perintah untuk menginput nilai n tersebut

3. import random - adalah perintah untuk mengimport built-in random yang telah tersedia di python

4. for i in range(jumlah): - adalah perintah untuk i sebagai integer dalam baris jumlah

5.    print("data ke", i+1,"=",(random.uniform(0.1,0.5))) - adalah perintah untuk menampilkan hasil yang telah di input dengan ketentuan random uniform mulai dari nilai 0.1 sampai 0.5

#### berikut gambaran programnya

![Latihan1](https://user-images.githubusercontent.com/92704969/141399850-04594873-d851-416e-9fd8-7c226b8ff029.png)


#### berikut hasil dari program saat dijalankan

![Latihan1_1](https://user-images.githubusercontent.com/92704969/141399853-1db12373-e2f4-4816-981a-ebb3bf5fbb71.png)


# Latihan 2

## Buat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan

### Flowchart program
#### Berikut flowchar untuk program menampilkan bilangan tersbesar dari n buah data yang diinputkan

![flowchart_latihan2](https://user-images.githubusercontent.com/92704969/141401230-ab1036af-3a19-478f-81b8-18fa96ac0983.png)

### penjelasan alur program
1. print("Menampilkan bilangan terbesar dari n buah data yang diinput") - adalah perintah untuk menampilkan judul program

2. max = 0 - adalah perintah untuk menampilkan nilai max yang adalah 0

3. while True: - adalah perintah untuk pengulangan hingga waktu yang tidak ditentukan

4.      a = int(input("Masukkan Bilangan: ")) - adalah perintah untuk menginput nilai integer

5.   if max < a: - adalah perintah untuk tipe data if atau jika, maksimal nilai lebih kecil dari a atau integer

6.      max = a - perintah untuk nilai maximal sama dengan a atau integer

7.    if a ==0: - perintah untuk tipe data if atau jika a sama dengan 0 maka

8.      break - perintah untuk mengakhiri pengulangan, jadi jika menginput nilai 0 maka pengulangan berakhir atau selesai

9. print("Bilangan Terbesar Adalah: ", max) - adalah perintah untuk menampilkan hasil bilangan yang terbesar dari angka-angka yang telah terinput

#### berikut gambaran programnya

![Latihan2](https://user-images.githubusercontent.com/92704969/141399855-c4399673-c158-42af-a183-8a9ad0e98900.png)

#### berikut hasil program saat dijalankan

![Latihan2_1](https://user-images.githubusercontent.com/92704969/141399856-f98b937c-5ceb-454a-81d4-82c3c9190fe1.png)


# Program 1
## Program untuk menghitung laba investasi

### Flowchart program
#### berikut flowchart dari program menghitung laba investasi

![flowchart_program1](https://user-images.githubusercontent.com/92704969/141401236-e26b5dec-9da5-4d41-afa3-74fd7ec9c289.png)

### Penjelasan alur program

print("Laba Investasi") - adalah untuk menampilkan judul

x = int(input("Uang Modal Awal: ")) - adalah untuk menginput nilai x sebagai modal awal

a = 0*x - a adalah bulan pertama, karena bulan pertama belum memiliki laba, jadi masih 0 dikali dengan x nilai uang modal awal

b = 0*x - b adalah bulan kedua, karena bulan kedua belum memiliki laba, jadi nilai x dari uang modal dikali dengan 0

c = 0.01*x - c adalah bulan ketiga, dan sudah memiliki laba 1%, jadi ditulis 0.01 bentuk sederhana dari 1% dikali dengan modal atau uang awal dengan nilai x

d = 0.01*x - d adalah bulan keempat, dan labanya 1%, jadi ditulis 0.01 dikalikan dengan nilai x yang adalah uang awal atau modal

e = 0.05*x - e adalah bulan kelima, dan laba pada bulan kelima sebesar 5%, maka ditulis 0.05 dikalikan dengan nilai x untuk nilai uang awal atau modal

f = 0.05*x - f adalah bulan keenam, dan laba pada bulan keenam sebesar 5%, maka ditulis 0.05 dikalikan dengan nilai x untuk nilai uang awal atau modal

g = 0.05*x - g adalah bulan ketujuh, dan laba pada bulan ketujuh sebesar 5%, maka ditulis 0.05 dikalikan dengan nilai x untuk nilai uang awal atau modal

h = 0.02*x - h adalah bulan kedelapan, dan laba pada bulan kedelapan sebesar 2%, maka ditulis 0.02 dikalikan dengan nilai x untuk nilai uang awal atau modal

y=[a,b,c,d,e,f,g,h] - adalah untuk menentukan syarat y yang berisi a,b,c,d,e,f,g,h

for i in range(len(y)): - adalah untuk perulangan data dengan isi data y, dengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke urutan yang diinputkan dari data y

    print("Laba Bulan Ke",i+1 ,"sebesar: ",y[i]) - untuk menampilkan hasil laba dari bulan ke 1 sampai terakhir

z=(a+b+c+d+e+f+g+h) - Z untuk data yang berisi hasil penjumlahan laba dari bulan pertama sampai bulan ke delapan

print("Jumlah Laba Selama 8 Bulan: ",z) - menampilkan hasil dari jumlah laba

#### berikut gambaran programnya

![Program1](https://user-images.githubusercontent.com/92704969/141399857-1cb9e117-3f5a-43fd-9a9f-82c396e4e42c.png)

#### berikut hasil dari program setelah dijalankan

![Program1_1](https://user-images.githubusercontent.com/92704969/141399858-622166ed-ccb5-4213-aa0d-4ea85f4576be.png)

## Sekian Terimakasih