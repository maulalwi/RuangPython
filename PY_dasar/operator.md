
# Operator

Operator adalah konstruksi dalam manipulasi nilai dalam operan.

**Pahami perhitungan dibawah ini :**
```python
4 + 3 = 7
```
**4** dan **3** adalah **operan**, sebagai nilai input dalam operasi.  
**+** adalah **operator**, kontruksi untuk memanipulasi nilai dalam operan.

# Macam-macam operator :

- Operator Aritmatika (Arithmetic Operators)
- Operator Penugasan (Assignment Operators)
- Operator Perbandingan (Comparison (Relational) Operators)
- Operator Logika (Logical Operators)
- Operator Bitwise (Bitwise Operators)
- Operator Keanggotaan (Membership Operators)
- Operator Identisas (Identity Operators)

## 1. Operator Aritmatika

Operasi perhitungan dasar. Dilakukan terhadap sesama tipe data numerik. 

**Macam-macam Operator Aritmatika :**

### Penjumlahan +
Menjumlahkan nilai dari masing-masing operan atau bilangan. 

### Pengurangan -
Mengurangi nilai operan di sebelah kiri menggunakan operan di sebelah kanan. 

### Perkalian *
Mengalikan operan / bilangan. 

### Pembagian /
Untuk membagi operan di sebelah kiri menggunakan operan di sebelah kanan. 

### Sisa Bagi %
Mendapatkan sisa pembagian dari operan di sebelah kiri operator ketika dibagi oleh operan di sebelah kanan. 

### Pangkat **
Memangkatkan operan disebelah kiri operator dengan operan di sebelah kanan operator. 

### Pembagian Bulat //
Sama seperti pembagian. Hanya saja angka dibelakang koma dihilangkan. 

**Contoh :**
```python
# Penjumlahan +
print(2 + 3)

# Pembagian Bulat //
bil1 = 11
bil2 = 2
print(bil1 // bil2)
```

**Output :**
``` shell
5
5
```

## 2. Operator Penugasan

Digunakan untuk memberikan nilai atau memodifikasi nilai dalam sebuah variabel. 

Mudahnya mengisi variabel. 

Nilai operan disebelah kiri harus variabel. 

**Macam-macam :**

### =
Sebuah operator penugasan sederhana, memasukan nilai di sebelah kanan tanda ke variable di sebelah kiri.

### +=
Operator penjumlahan dan penugasan, menjumlahkan nilai di sebelah kanan dengan variable di sebelah kiri, kemudian hasilnya di masukan ke variable di sebelah kiri. 


### -=
Operator pengurangan dan penugasan, mengurangi variable di sebelah kiri dengan nilai di sebelah kanan, kemudian hasilnya dimasukan lagi ke variable di sebelah kiri.

### *=
Operator perkalian dan penugasan, nilai di sebelah kanan dikali dengan variable di sebelah kiri, kemudian hasilnya dimasukan ke variable di sebelah kiri.

### /=
Operator pembagian dan penugasan, membagi variable di sebelah kiri dengan nilai di sebelah kanan, kemudian hasilnya dimasukan ke variable di sebelah kiri.

### %=
Operator modulus dan penugasan, melakukan operasi modulus dari variable di sebelah kiri dengan nilai di sebelah kanan, kemudian hasilnya dimasukan ke variable di sebelah kiri. 

### **=
Operator eksponensial (pemangkatan) dan penugasan, menghitung variable di sebelah kiri bila dipangkatkan dengan nilai di sebelah kanan, kemudian nilainya di masukan ke variable di sebelah kiri.

### //=
Operator pembagian pembulatan ke bawah dan penugasan, melakukan pembagian variable di sebelah kiri dengan nilai di sebelah kanan, bila hasilnya pecahan, maka dibulatkan ke bawah dan hasilnya dimasukan ke variable di sebelah kiri.

**Contoh :**
```python
# Operator penugasan sederhana
a = 7
print(a)

# Operator penugasan penjumlahan
b = 2
b += 3
print(b)

# Operator penugasam sisa bagi
c = 11
c %= 2
print(c)
```
**Output :**
```shell
7
5
1
```

## 3. Operator perbandingan

Digunakan untuk membandingkan dua atau lebih data.

Data yang dibandingkan boleh berada dalam variabel atau data yang ditulis secara langsung. 

Ada banyak tipe data bisa dibandingkan. 

Hasil operasi perbandingan adalah tipe data Boolean(True atau False).

**Macam-macam operator Perbandingan :**

### 1. Sama dengan ==
Jika masing-masing operan memiliki nilai yang sama, maka kondisi bernilai benar atau True.

### 2. Tidak sama dengan !=
Akan menghasilkan nilai kebalikan dari kondisi sebenarnya.

### 3. Lebih besar dari >
Jika nilai operan kiri lebih besar dari nilai operan kanan, maka kondisi menjadi benar.

### 4. Lebih kecil dari <
Jika nilai operan kiri lebih kecil dari nilai operan kanan, maka kondisi menjadi benar.

### 5. Lebih besar atau sama dengan >=
Jika nilai operan kiri lebih besar dari nilai operan kanan, atau sama, maka kondisi menjadi benar.

### 6. Lebih kecil atau sama dengan <=
Jika nilai operan kiri lebih besar dari nilai operan kanan, atau sama, maka kondisi menjadi benar.

**Contoh :**
```python
print('hello' == 'hello') 

print(11 <= 7)
```
**Output :**
```shell
True
False
```

## 4. Operator Logika

Adalah operasi yang input dan outputnya hanya memiliki dua keadaan yaitu True dan False (Boolean). 

Nilai True atau False yang didapat operator logika bisa didapat secara langsung dari tipe data lain secara langsung. 

Data yang ada tidak di konversi ke tipe Boolean, dan data tidak berubah. 

### Bernilai False

Operasi logika akan menganggap suatu data bernilai False jika :

Data yang secara langsung diberi nilai False, contoh :  
`a = False`

Data bertipe numerik dengan nilai 0, contoh :  
`a = 0`

Data bertipe string dengan nilai kosong, contoh :  
`a = '""`

Data bertipe list dengan nilai kosong, contoh :  
`a = []`

Data bertipe tuple dengan nilai kosong, contoh :  
`a = ()`

Data bertipe dictionary dengan nilai kosong, contoh :   
`a = {}`

### Bernilai True

 Operasi logika akan menganggap suatu data bernilai True Jika :

Data yang secara langsung diberi nilai True, contoh :  
`a = True`

Data bertipe numerik dengan nilai selain 0, contoh :  
`a = 1`  
`b = -3`

Data bertipe string dengan nilai selain kosong, contoh :  
`a = "a"`
`b = 'False'`

Data bertipe list dengan nilai selain kosong, contoh :  
`a = [1,3]`

Data bertipe tuple dengan nilai selain kosong, contoh :  
`a = ('satu','dua')`

Data bertipe dictionary dengan nilai selain kosong, contoh :  
`a = {'a': 'satu', 'b': 2}`

### Operator logika 

#### AND

`and`

Jika **kedua operan bernilai True**, maka hasil **True**. 
Jika **salah satu atau kedua operan False**, maka hasil **False**. 

#### OR

`or`

Jika **kedua operan bernilai False**, maka hasil **False**. 
Jika **salah satu atau kedua operan True**, maka hasil **True**.

#### NOT

`not`

Membalik nilai kebenaran pada operan. 
Misal, jika nilai True maka menjadi False, juga sebaliknya. 

## 5. Operator Bitwise

Bekerja berdasarkan bit dari suatu bilangan. 

Sebelum dilakukan operasi bitwise input (berupa bilangan desimal) harus diubah ke bentuk biner(bilangan dua. 1 dan 0) terlebih dahulu.

Kemudian hasil output yang juga dalam bentuk biner, sebelum ditampilkan akan diubah ke bentuk desimal terlebih dahulu.

Sehingga meskipun operasi berjalan dalam bentuk bit, kita tidak akan melihatnya, hanya bisa melihat hasilnya.

**Macam-macam :**

### AND &
Operator biner AND, memeriksa apakah operan di sebelah kiri dan operan sebelah kanan mempunyai angka biner 1 di setiap bit. Jika keduanya bernilai 1 maka bit hasil operasi akan bernilai 1.

### OR |
Operator biner OR, memeriksa apakah operan di sebelah kiri dan operan sebelah kanan mempunyai angka biner 1 di setiap bit. Jika salah satunya bernilai 1 maka bit hasil operasi akan bernilai 1.

### XOR ^
Operator biner XOR, memeriksa apakah operan di sebelah kiri dan operan sebelah kanan mempunyai angka biner 1 di setiap bit. Jika keduanya bernilai 1 maka bit hasil operasi akan bernilai 0.

### Negasi ~
`~x berarti -x-1`

### Left Shift <<
Menambahkan nilai 0 sebanyak n kali. 

### Right Shiff >>
Operator penggeser biner ke kiri, deret bit akan digeser ke kiri sebanyak n kali.

**Contoh :**

```python
# Karakter Enter
print('\n')
print('# Penggunaan Bitwise & | ^')

a = 5
b = 6

print(a)
print(bin(a))
print(b)
print(bin(b))

print('\n')
print('# Bitwise &')

c = a & b

print(c)
print(bin(c))

print('\n')
print('# Bitwise |')
c = a | b

print(c)
print(bin(c))

print('\n')
print('# Bitwise ^')
c = a ^ b

print(c)
print(bin(c))
```

**Output :**

```shell
# Penggunaan Bitwise & | ^
5
0b101
6
0b110


# Bitwise &
4
0b100


# Bitwise |
7
0b111


# Bitwise ^
3
0b11
```

**Contoh :**

```python
print('# Bitwise Negasi ~')
a = ~1
b = ~5

print(a)
print(bin(a))

print(b)
print(bin(b))

# Karakter Enter
print('\n')
print('# Penggunaan Bitwise Right and Left Shift')

a = 11
b = 2

print(a)
print(bin(a))
print(b)
print(bin(b))

print('\n')
print('# Bitwise <<')

c = a << b

print(c)
print(bin(c))

print('\n')
print('# Bitwise >>')
c = a >> b

print(c)
print(bin(c))
```

**Output :**

```shell
# Bitwise Negasi ~
-2
-0b10
-6
-0b110


# Penggunaan Bitwise Right and Left Shift
11
0b1011
2
0b10


# Bitwise <<
44
0b101100


# Bitwise >>
2
0b10
```

## 6. Operator Keanggotaan

Operator keanggotaan akan memberikan nilai bertipe Boolean, yaitu `True` atau `False`.

Operator keanggotaan hanya bisa diterapkan pada variable berjenis **sequence(list, tuple, dan dictionary)**. 

### in
Jika anggota ada maka `True`. 
Jika anggota tidak ada maka `False`. 

### not in
Jika anggota ada maka `False`. 
Jika anggota tidak ada maka `True`. 

**Contoh :**

```python
list = ['satu', 'dua', 'tiga', 'empat']

print('dua' in list)

print('dua' not in list)
```

**Output :**

```
True
False
```

## 7. Operator Identitas

Sebuah data bisa dilihat sama tetapi mempunyai tipe berbeda serta alamat obyek dalam memori yang berbeda. 

Untuk mengecek apakah dua data memiliki obyek yg sama di Python bisa menggunakan cara manual dengan fungsi id(), atau dengan operator Identitas yang mengembalikan nilai Boolean. 

### is
Jika id sama maka `True`. 
Jika id tidak sama maka `False`.

### is not
Jika id sama maka `False`. 
Jika id tidak sama maka `True`. 

**Contoh :**
```python
a = 8
b = 4 + 4

print(id(a))
print(id(b))

print(a is b)

print(a is not b)

print('-------')

a = 8
b = 7

print(id(a))
print(id(b))

print(a is b)
```

**Output :**

```shell
4146830424
4146830424
True
False
-------
4146830424
4146830408
False
```

## 8. Prioritas Eksekusi Operator

Dari semua operator, masing-masing mempunyai urutan prioritas yang nantinya prioritas pertama akan dilakukan paling pertama, begitu seterusnya sampai dengan prioritas terakhir.

1. `**` **Aritmatika**
2. `~, +, -` **Bitwise**
3. `*, /, %, //` **Aritmatika**
4. `+, -` **Aritmatika**
5. `>>, <<` **Bitwise**
6. `&` **Bitwise**
7. `^, |` **Bitwise**
8. `<=, <, >, >=` **Perbandingan**
9. `<> , ==, !=` **Perbandingan**
10. `=, %=, /=, //=, -=, +=, *=, **=` **Penugasan**
11. `is, is not` **Identitas**
12. `in, not in` **Keanggotaan**
13. `not, or, and` **Logika**

---

`Update : 2020-05-28`

