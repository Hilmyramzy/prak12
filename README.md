Nama : Hilmy syaddad ramzy

NIM : 312210162

TI22A1

Python String

String adalah jenis yang paling populer di Python.

Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.

Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").

Membuat string semudah memberi nilai pada sebuah variabel.

![prak12](https://user-images.githubusercontent.com/115677769/209867054-241f9b09-7ef4-4909-ba03-401d00ddaf17.png)


Penjelasan Latihan 1
Untuk menghitung jumlah karakter, gunakan fungsi len().

# Menghitung jumlah karakternya
print(len(txt))
Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku [ ] dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya. Untuk mengambil karakter terakhir, gunakan index [-1]. Sedangkan untuk mengambil karakter index ke-2 sampai ke-4, gunakan index [2:5].


# Mengambil karakter terakhir
print(txt[-1])
# Mengambil karakter index ke-2 sampai index ke-4 (llo)
print(txt[2:5])
Jika ingin menghilangkan spasi pada string, gunakan method replace(). Method replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.


Di dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan (txt.replace(" ", "")) dan kedua dengan cara (txt.replace(txt[5], "")).

# Menghilangkan spasi pada text tersebut (HelloWorld)
print(txt.replace(" ", ""))
Untuk mengubah huruf menjadi besar, gunakan method upper(). Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method lower().


# Mengubah text menjadi huruf besar
print(txt.upper())
# Mengubah text menjadi huruf kecil
print(txt.lower())
Untuk mengganti karakter 'H' dengan karakter 'J', gunakan method replace().


# Mengganti karakter H dengan karakter J
print(txt.replace("H", "J"))
print()

OUTPUT latihan 1

![Screenshot (123)](https://user-images.githubusercontent.com/115677769/209867202-b624b1fc-05b2-4176-a0fc-7a14d0d13a75.png)

LATIHAN 2
![prak12,1](https://user-images.githubusercontent.com/115677769/209867302-e15cac4f-dc32-4009-bef8-0fcf598101a8.png)

Penjelasan Latihan 2
Untuk memasukkan variable ke dalam string, tambahkan kurung kurawal {} untuk menempatkan variable sebelumnya.

  umur = 24
  txt = "\nHello, nama saya john, dan umur saya adalah {0} tahun\n"

  print(txt.format(umur))
  
  OUTPUT latihan 2
  ![Screenshot (124)](https://user-images.githubusercontent.com/115677769/209867382-2f44a3bf-6934-43e2-94a7-a1ae4c91854a.png)
  
  SELESAI.


