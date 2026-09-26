# Syntax

## Definisi

Syntax dalam Python adalah seperangkat aturan dasar yang menentukan bagaimana kita harus menulis kode agar bisa dipahami dan dieksekusi oleh komputer. Ibarat tata bahasa dalam bahasa manusia, sintaksis memastikan instruksi kita jelas dan tidak menimbulkan pesan error saat program dijalankan.

Python sangat terkenal karena sintaksnya yang bersih, minimalis, dan sangat mirip dengan bahasa Inggris sehari-hari. Bahasa ini sengaja dirancang agar mudah dibaca (readable), sehingga pemrogram bisa lebih fokus pada logika penyelesaian masalah daripada pusing memikirkan simbol-simbol yang rumit.

## Aturan Dasar

### Indentasi adalah wajib

Python menggunakan spasi di awal baris (biasanya 4 spasi atau 1 tab) untuk menandai sebuah grup atau blok kode (seperti di dalam perulangan atau fungsi), bukan menggunakan tanda kurung kurawal `{}` seperti bahasa pemrograman lainnya.

### Sensitif terhadap huruf besar/kecil (Case-Sensitive)

Penamaan variabel `Teks` dan `teks` akan dianggap sebagai dua variabel yang sama sekali berbeda oleh Python.

### Tanpa titik koma

Kamu tidak wajib menambahkan titik koma (`;`) di akhir setiap baris perintah.

### Komentar menggunakan tanda `#`

Teks apa pun yang ditulis setelah tanda pagar (#) di satu baris yang sama akan diabaikan oleh sistem dan berfungsi murni sebagai catatan penjelasan untuk manusia.

## Contoh kode

Berikut adalah contoh penerapan Syntax Python dalam Python:

```python
# Ini adalah contoh komentar di Python
nama_pengguna = "Andi" # Case-sensitive, 'nama_pengguna' berbeda dengan 'Nama_Pengguna'

# Contoh aturan indentasi pada blok logika kondisional
if nama_pengguna == "Andi":
    # Baris ini wajib menjorok ke dalam (indentasi) karena bagian dari 'if'
    print("Halo, Andi! Selamat datang.")
else:
    # Baris ini juga wajib indentasi karena bagian dari 'else'
    print("Maaf, pengguna tidak dikenal.")
```