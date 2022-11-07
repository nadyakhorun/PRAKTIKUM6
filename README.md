KONDISI DAN PERULANGAN

Lab 2 Struktur Kondisi

Latihan 1

• Buat program sederhana dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if!

Langkah - langkah

1. Buat programnya terlebih dahulu seperti gambar di bawah ini

![2022-11-07 (2)](https://user-images.githubusercontent.com/115801823/200342407-833d3d9f-244b-4ac2-90fb-134bf6df0161.png)

    # menentukan bilangan
    print('Menentukan bilangan terbesar dari 2 bilangan')
    a = int(input("Masukkan nilai A:"))
    b = int(input("Masukkan nilai B:"))
    if a > b:
        print("A =", a, "yang terbesar")
    elif b > a:
        print("B=", b, "yang terbesar")

2. Hasil run

![run 1](https://user-images.githubusercontent.com/115801823/200343024-7335a6f2-3318-4870-a88e-8c916aebb733.PNG)

Latihan 2

• Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkecil.

Langkah - langkah

1. Buat programnya terlebih dahulu seperti gambar di bawah ini

![2022-11-07 (4)](https://user-images.githubusercontent.com/115801823/200343528-a0af3a88-045e-493d-b580-5287ebbb4912.png)

    print("_____Mengurutkan bilangan dari yang terkecil ke yang terbesar_____")
    print("Masukan 3 bilangan yang akan diurutkan:")
    a = int(input("masukkan bilangan 1 = "))
    b = int(input("masukkan bilangan 2 = "))
    c = int(input("masukkan bilangan 3 = "))

    if a < b and a < c:
        if b < c:
            print(a, b, c)
        else:
            print(a, c, b)
    elif b < a and b < c:
        if a < c:
            print(b, a, c)
        else:
            print(b, c, a)
    else:
        if a < b:
            print(c, a, b)
        else:
            print(c, b, a)
2. Hasil run

![run 2](https://user-images.githubusercontent.com/115801823/200343858-d4159a49-fc39-489e-acca-5fe60504ee11.PNG)

Lab 3 Perulangan

Latihan 1

• Buat program dengan perulangan bertingkat (nested) for yang menghasilkan output sebagai berikut:

Langkah - langkah

1. Buat programnya terlebih dahulu seperti gambar di bawah ini

![2022-11-07 (6)](https://user-images.githubusercontent.com/115801823/200344363-77a4794d-d17e-482a-b8e3-9987b05b3772.png)

    for i in range(0,10):
        print()
        print(i, end="\t")
        for j in range(1,10):
            print(i+j,end="\t")
2. Hasil run

![run 3](https://user-images.githubusercontent.com/115801823/200344859-8082684d-5830-4558-8570-c1c8f0aa0afe.PNG)

Latihan 2

• Tampilkan n bilangan acak yang lebih kecil dari 0.5.

• nilai n diisi pada saat runtime

• anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya

Langkah - langkah

1. Buatlah programnya terlebih dahulu seperti gambar dibawah ini

![2022-11-07 (8)](https://user-images.githubusercontent.com/115801823/200345201-0d8d9754-4034-44f0-9ee6-32b31de1e522.png)

    from random import random

    n = int(input("Masukan Beberapa perulangan : "))
    while n == n:
        break
    for i in range(n):
        bil = random() % 0.5
        print("Perulangan ke : ", bil)
2. Hasil run

![run 4](https://user-images.githubusercontent.com/115801823/200345529-50b9ede0-e071-4cad-9531-23e106b72360.PNG)

MODUL PRAKTIKUM 2 DAN 3

Labpy02 dan Labpy03

Labpy02

• Buat program sederhana dengan input tiga buah bilangan, dari ketiga bilangan tersebut tampilkan bilangan terbesarnya. Gunakan statement if.

Langkah - langkah

1. Buatlah flowchart dari mencari angka terbesar dari 3 bilangan seperti gambar dibawah ini

![200159462-6b7e6bcb-8a43-4d48-a4c4-5bf8bda85a42](https://user-images.githubusercontent.com/115801823/200346173-1bd4dc03-340d-4bcb-985f-6777380dce97.png)

2. Buatlah program codenya seperti gambar dibawah ini

![2022-11-07 (10)](https://user-images.githubusercontent.com/115801823/200346499-038a8a43-015c-46ba-a3d8-12f71b49cb0b.png)

      a, b, c = (
          int(input('Masukkan nilai a: ')),
          int(input('Masukkan nilai b: ')),
          int(input('Masukkan nilai c: '))
      )
      if a > b and a > c:
          print('A yang terbesar')
      elif b > a and b > c:
          print('B yang terbesar')
      else:
          print('C yang terbesar')
2. Hasil dari Run

![run 5](https://user-images.githubusercontent.com/115801823/200347031-5b3c364b-fae0-432e-a3c0-079b63541996.PNG)

Labpy03

Latihan 1

Flowchart dari latihan 1

![200159707-ccb1abdb-be69-4849-96c8-6c02c439d199](https://user-images.githubusercontent.com/115801823/200347193-02e0f924-4055-4a30-8bd3-a4fad535dd5f.png)

Algoritma dari latihan 1

Menampilkan n bilangan acak yang lebih kecil dari 0,5, nilai n diisi pada saat runtime.

1.Memasukan/ import fungsi RANDOM terlebih dahulu

2.Deklarasi integer , masukkan jumlah n :

3.Memasukan deskripsi kombinasi for untuk menyelesaikannya.

4.Memasukan nilai jumlah (n) : 5

5.Mencetak data ke 1 sampai 5 dengan hasil nilai kurang dari 0,5.

6.Selesai

Langkah - langkah

1. Buat program codenya seperti gambar dibawah ini

![2022-11-07 (12)](https://user-images.githubusercontent.com/115801823/200347552-40827c10-6bef-4cc9-be0a-e3a78d7336d6.png)

    print("bilangan acak yang lebih kecil dari o.5")
    import random

    n = int(input("masukan nilai:"))
    a = 0
    for c in range(n):
        a += 1
        b = random.uniform(.0, .5)
        print("data ke:", a, "==>", b)

    print("selesai")
2. Hasil run

![run 6](https://user-images.githubusercontent.com/115801823/200347936-e5ea8f6a-f620-416e-8596-bd4bc256b959.PNG)

Latihan 2

Flowchart dari latihan 2

![200159970-42dd1c12-2af8-416d-b808-822ed3c3c7fc](https://user-images.githubusercontent.com/115801823/200348255-0af9262f-70eb-47dd-aa24-cd119827c0d2.png)

Algoritma latihan 2

Membuat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan.Masukkan angka 0 untuk berhenti

1.Mulai

2.Mencetak "latihan 2"

3.Mencetak "menampilkan bilangan, berhenti ketika bilangan 0, menampilkan bilangan terbesar"

4.integer max = 0

5.Menggunakan fungsi perulangan while true, hingga menampilkan perulangan sampai batas tertentu.

6.Memasukan bilangan integer pada "a"

7.Menggunakan fungsi if jika max kurang dari nilai a, maka max sama dengan a

8.Mengunakan fungsi if jika nilai a adalah 0 maka fungsi break artinya perulangan berhenti jika menulis nilai 0.

9.Mencetak nilai paling terbesarv setelah break, sehingga menampilkan nilai terbesar diantara bilangan tersebut dalam perulangan.

10.Selesai

Langkah - langkah

1. Buatlah program code seperti gambar dibawah ini

![2022-11-07 (15)](https://user-images.githubusercontent.com/115801823/200348606-f7d17ab9-4683-45dc-985f-18f420f5b845.png)

    print("menampilkan bilangan, berhenti ketika bilangan 0, dan menampilkan bilangan terbesar")

    max = 0
    while True:
        angka = int(input("masukan bilangan : "))
        if max < angka:
            max = angka
        if angka == 0:
            break
    print("bilangan terbesarnya adalah = ", max)
    print("selesai")
2. Hasil run

![run 7](https://user-images.githubusercontent.com/115801823/200349011-98b2664f-0b25-4fc3-8ec9-f222723728a6.PNG)

Program 1

Flowchart dari program 1

![200160200-2f3db728-7d3d-48c0-b21a-b8d3bf11438b](https://user-images.githubusercontent.com/115801823/200349134-bdde8962-47de-401f-b0b8-e91ff808b329.png)

Algoritma dari program 1

1.Mulai

2.Mencetak latihan1

3.Mencetak "Program menghitung laba dengan modal awal 100 juta"

4.Membuat Note

5.Mencetak Bulan pertama dan kedua = 0%

6.Mencetak bulan ke 3 = 1%

7.Mencetak bulan ke 5 = 5%

8.Mencetak bulan ke 8 = 2%

9.integer a = 100.000.000( modal awal)

10.Menggunakan fungsi looping for pada nilai x 1-9 untuk menampilkan bulan 1 sampai bulan 8.

11.Menggunakan fungsi if, untuk menghitung laba bulan 1 sampai 8

12.bulan pertama dan kedua laba adalah 0

13.bulan ke 3 dan ke 4 mendapat laba 1% sehingga modal di kali 1% = keuntungan

14.bulan ke 5 mendapatkan laba 5%, sehingga modal dikali 5% = keuntungan

15.Bulan ke 8 mmendapatkan laba 2% sehingga keuntungan menurun dari bulan sebelumnya, modal dikali 2% = keuntungan.

16.Menghitung jumlah total laba dengan menjumlah keuntungan dari bulan ke 1 sampai bulan 8, hasilnya adalah total keuntungan yang didapat.

17.Selesai

Langkah - langkah

1. Buatlah program codenya seperti gambar dibawah ini

![2022-11-07 (16)](https://user-images.githubusercontent.com/115801823/200349336-8d96a710-2ecb-471e-9f67-469bf78d6b9f.png)

      x = 100000000
      sum = 0
      y = 0
      lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2]
      print("modal awal seorang pengusaha :', x")
      for i in lb:
          sum = sum + i
          y += 1
          print("#laba bulan ke - ", y, "sebesar :", i)

          print("  TOTAL LABA YANG DIDAPAT ADALAH :", sum)
2. Hasil run

![run 8](https://user-images.githubusercontent.com/115801823/200349525-e1c11a7c-b35e-4645-9c02-99cb14c80ab7.PNG)

TERIMA KASIH.
