# Praktikum12

## Python String

- String adalah jenis yang paling populer di Python.
- Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.
- Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").
- Membuat string semudah memberi nilai pada sebuah variabel.

## Latihan1
![img](picture/pic1.png)

### penjelasan latihan 1

- Untuk mengitung jumlah karakter,gunakan fungsi len().
-Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku `[ ]` dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya. Untuk mengambil karakter terakhir, gunakan **index [-1]**. Sedangkan untuk mengambil karakter index ke-2 sampai ke-4, gunakan **index [2:5]**.
- Jika ingin menghilangkan spasi pada string, gunakan method replace(). Method replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.
- Di dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan (txt.replace(" ", "")) dan kedua dengan cara `(txt.replace(txt[5], ""))`
- Untuk mengubah huruf menjadi besar, gunakan method upper(). Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method lower().
- untuk mengganti karakter 'H' dengan karakter 'J', gunakan method replace()

### Output latihan1
![img](picture/pic2.png)

## latihan2
![img](picture/pic3.png)

### penjelasan latihan 2

Untuk memasukkan variable ke dalam string, tambahkan kurung kurawal `{}` untuk menempatkan variable sebelumnya.

      umur = 24
      txt = "\nHello, nama saya john, dan umur saya adalah {0} tahun\n"

      print(txt.format(umur))

### Output latihan 2
![img](picture/pic4.png)

## Sekian, Terima kasih