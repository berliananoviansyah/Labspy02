# Labspy02
Tugas pada power point 2 pertemuan 7

# PERTEMUAN 7
### NAMA: BERLIANA NOVIASNYAH
### KELAS: TI. 20. A. 1
### NIM: 312010373
___________________________________________________________________________________

 Pada pertemuan 7 tugas PPT ke-2 ini, saya diberikan beberapa tugas oleh dosen saya yaitu 

![Tugas Praktikum 2](https://user-images.githubusercontent.com/72906579/98377632-a5376480-2077-11eb-914b-7edfddf5d866.png)

untuk mencari sebuah nilai maksimal dari 3 data yang sebelumnya telah diinput, dan setelah mendapat nilai maksimalnya, dirubah menjadi dalam sebuah bentuk flowchart.

## TUGAS PRAKTIKUM 2
##### MENGINPUT DATA DAN MENCARI NILAI MAX
________________________________________________________________________________________
Pertama-tama disini saya akan mencoba untuk menginput 3 data dengan menggunakan syntax berikut terlebih dahulu.
```python
a = int(input("Masukkan bilangan 1: "))
b = int(input("Masukkan bilangan 2: "))
c = int(input("Masukkan bilangan 3: "))
```
Masukan syntax tersebut dengan angka yang kalian inginkan. 

![PPT2LAT1](https://user-images.githubusercontent.com/72722965/98512346-c3c87600-2298-11eb-8678-cb72e02a1723.PNG)

Jika sudah mendapat tampilan seperti gambar diatas, maka kalian sudah berhasil menginput ketiga data tersebut. <br>

Langkah selanjutnya adalah mencari tahu nilai terbesar (max) dari ketiga data tersebut. Sebelum memulainya kalian harus memasukan terlebih dahulu berapa jumlah data yang akan kalian kerjakan dari ketiga data tersebut dengan syntax <br>
```python
N=int(input("banyaknya data = "))
```
Karena disini saya diberi tugas mencari nilai max dari ketiga data maka saya akan menggunkan semua data diatas.

```python
if N>0:
    i=1
    x=int(input("data ke -"+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("data ke -"+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
```
Selanjutnya kalian bisa langsung  memasukan syntax ini untuk melengkapi syntax diatas supaya bisa berjalan dengan baik seperti pada gambar dibawah ini.

[latt2](https://user-images.githubusercontent.com/72722965/98513325-3f76f280-229a-11eb-9384-3b265b695e33.PNG)

Maka jika digabungkan, cara untuk mencari nilai max dari ketiga data yang diinputkan adalah dengan menggunakan syntax
```python
N=int(input("banyaknya data = "))
if N>0:
    i=1
    x=int(input("data ke -"+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("data ke -"+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
```
Seperti inilah hasil akhirnya 

![hasil](https://user-images.githubusercontent.com/72722965/98513597-aeece200-229a-11eb-82e3-3bea9c3f9b71.PNG)


##### MERUBAH DATA DIATAS MENJADI DALAM BENTUK FLOWCHART
__________________________________________________________________________________
Setelah kalian mendapatkan semua data diatas langkah selanjutnya adalah mengubahnya menjadi dalam bentuk flowchart seperti ini

![flowchart](https://user-images.githubusercontent.com/72722965/98514576-4272e280-229c-11eb-9d0f-2ea264dc6f5c.PNG)
Untuk bisa mendapatkan hasil flowchart diatas, maka kalian harus mendownload flowgorithm terlebih dahulu. Download lah pada web resminya yaitu 
```python
http://www.flowgorithm.org/download/index.htm
```
Download lah yang sesuai dengan laptop kalian agar tidak terjadi kendala saat sedang mengoperasikannya.

![Download Flow](https://user-images.githubusercontent.com/72906579/98425077-74325080-20c6-11eb-8cc6-4a64210e290a.png)

Setelah mendapat tampilan seperti dibawah ini kalian bisa mengklik pada bagian garis hitamnya

![Flow Step1](https://user-images.githubusercontent.com/72906579/98389639-e5eaaa00-2086-11eb-9dd2-107a642334ff.png)

Pada tampilan diatas kalian dapat memilih menu mana yang kalian butuhkan.

Jika kalian sudah mengerjakannya hingga akhir, maka step akhir adalah kalian hanya perlu mengecek apakah flowchart tersebut sudah bekera dengan baik atau belum dengan cara sebagai berikut

![Flow Step2](https://user-images.githubusercontent.com/72906579/98391855-cbfe9680-2089-11eb-8062-164af41a5509.png)

Jika sudah me 'run' berkali kali dan mendapatkan jawaban sama yang sesuai itu berbarti flowchart yang kalian buat sudah benar dan bekerja dengan baik.