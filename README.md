# Belajar Python dengan RacikCode

Selamat datang di panduan belajar Python yang menarik di platform RacikCode! Di sini Anda akan mempelajari dasar-dasar bahasa pemrograman Python dan konsep-konsep penting lainnya. Panduan ini didesain untuk membantu Anda memulai perjalanan belajar Python dengan mudah dan menyenangkan.

## Daftar Isi

- [Pendahuluan](#pendahuluan)
- [Instalasi Python](#instalasi-python)
- [Hello, World!](#hello-world)
- [Variabel dan Tipe Data](#variabel-dan-tipe-data)
- [Percabangan](#percabangan)
- [Perulangan](#perulangan)
- [Fungsi](#fungsi)
- [Modul dan Paket](#modul-dan-paket)
- [Manipulasi String](#manipulasi-string)
- [List, Tuple, dan Dictionary](#list-tuple-dan-dictionary)
- [File Input/Output](#file-inputoutput)

## Pendahuluan

Python adalah bahasa pemrograman yang populer dan mudah dipelajari. Dalam panduan ini, kami akan mengajarkan dasar-dasar Python dan memberikan contoh kode yang interaktif untuk membantu Anda memahaminya dengan baik.

## Instalasi Python

Sebelum memulai, pastikan Anda telah menginstal Python di komputer Anda. Untuk petunjuk instalasi langkah demi langkah, Anda dapat mengunjungi [dokumentasi resmi Python](https://www.python.org).



## Hello, World!

Mari kita mulai dengan program sederhana "Hello, World!" untuk memastikan instalasi Python Anda berjalan dengan baik. Berikut ini contoh kode yang perlu Anda tulis:

```python
print("Hello, World!")
```

## Variabel dan Tipe Data

Dalam Python, Anda dapat menggunakan variabel untuk menyimpan data dan memberikannya nama yang dapat diidentifikasi. Berikut adalah contoh penggunaan variabel dalam Python:

```python
nama = "Fulan"
umur = 25
```

## Percabangan
Percabangan merupakan salah satu konsep penting dalam pemrograman yang memungkinkan eksekusi kode berdasarkan kondisi-kondisi tertentu. Dalam bahasa pemrograman Python, terdapat beberapa jenis percabangan yang sering digunakan, yaitu if, if-else, dan if-elif-else. Dalam README ini, kita akan menjelaskan penggunaan dan sintaksis dari masing-masing jenis percabangan tersebut.

## 1. Percabangan if
Percabangan if digunakan untuk menjalankan blok kode jika suatu kondisi bernilai benar (True). Berikut adalah format dasar dari percabangan if:
```
if kondisi:
    # blok kode yang akan dijalankan jika kondisi benar
```
Contoh penggunaan percabangan if:

```umur = 18
if umur >= 18:
    print("Anda sudah cukup umur.")
```
Output:
```
Anda sudah cukup umur.
```
## 2. Percabangan if-else
Percabangan if-else digunakan untuk menjalankan blok kode jika suatu kondisi bernilai benar (True), dan menjalankan blok kode lain jika kondisi tersebut bernilai salah (False). Berikut adalah format dasar dari percabangan if-else:
```
if kondisi:
    # blok kode yang akan dijalankan jika kondisi benar
else:
    # blok kode yang akan dijalankan jika kondisi salah

```
Contoh penggunaan percabangan if-else:
```
umur = 15
if umur >= 18:
    print("Anda sudah cukup umur.")
else:
    print("Anda belum cukup umur.")
```
Output
```
Anda belum cukup umur.
```
## 3. Percabangan if-elif-else
Percabangan if-elif-else digunakan untuk mengevaluasi beberapa kondisi secara berurutan dan menjalankan blok kode sesuai dengan kondisi yang terpenuhi. Blok kode di dalam bagian elif akan dievaluasi hanya jika kondisi sebelumnya tidak terpenuhi. Berikut adalah format dasar dari percabangan if-elif-else:
```
if kondisi1:
    # blok kode yang akan dijalankan jika kondisi1 benar
elif kondisi2:
    # blok kode yang akan dijalankan jika kondisi2 benar
else:
    # blok kode yang akan dijalankan jika semua kondisi salah

```
Contoh penggunaan percabangan if-elif-else:
```
umur = 25
if umur < 18:
    print("Anda belum cukup umur.")
elif umur >= 18 and umur < 21:
    print("Anda sudah cukup umur, silakan tonton filem ini")
else:
    print("Anda sudah boleh nonton.")
```
Output :
```
Anda sudah boleh nonton.
```

Itulah penjelasan mengenai percabangan dalam Python. Dengan menggunakan percabangan, kita dapat mengendalikan alur program berdasarkan kondisi-kondisi tertentu.