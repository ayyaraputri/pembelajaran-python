# 🐍 Python Fundamental Learning 
**Belajar Dasar Pemrograman Python dari Nol hingga Paham!**

Selamat datang di repository **Python Fundamental Learning**!
Repo ini berisi kumpulan materi, contoh kode, dan catatan pembelajaran yang dirancang untuk membantu pemula memahami konsep dasar bahasa pemrograman **Python** secara bertahap, rapi, dan mudah dipelajari.

---

## 🎯 Tujuan Pembelajaran
Repo ini disusun untuk membantu kamu:
* Memahami **dasar-dasar sintaks Python** dan cara kerja interpreter
* Menguasai **variabel, tipe data** (termasuk *list*, *tuple*, *dictionary*, *set*)
* Menggunakan **kontrol alur** seperti `if`, `elif`, `else`, dan *loop* `for`, `while`
* Mengenal **fungsi, modul**, dan konsep fundamental lainnya
* Membiasakan praktik menulis kode Python yang **'Pythonic'** (rapi dan efisien)
* Menjadi pondasi untuk belajar **OOP (Object-Oriented Programming)**, *data science*, dan topik lanjutan lainnya

---

## 📘 Materi Pembelajaran

### 🔹 1. Pengenalan Python
* Apa itu Python? (Bahasa interpreter, *High-Level*)
* Cara kerja interpreter dan PVM (Python Virtual Machine)
* Struktur dasar program dan Indentasi

### 🔹 2. Variabel & Tipe Data Dasar
* Integer, Float, String, Boolean
* Konstanta (Konvensi penulisan)
* *Type Hinting* (Intro)

### 🔹 3. Struktur Data Koleksi
* **List** (Daftar)
* **Tuple**
* **Dictionary** (Kamus)
* **Set**

### 🔹 4. Operator
* Aritmatika
* Perbandingan (*Comparison*)
* Logika (`and`, `or`, `not`)
* Penugasan (*Assignment*)

### 🔹 5. Kontrol Alur (Flow Control)
* `if` / `elif` / `else`
* Loop **`for`** (dengan *range* dan iterasi koleksi)
* Loop **`while`**
* `break` dan `continue`

### 🔹 6. Fungsi
* Deklarasi fungsi dengan `def`
* Parameter, Argumen, dan *Return Value*
* Fungsi Lambda (Intro)

### 🔹 7. Input / Output & File Handling (Dasar)
* Fungsi `input()` dan `print()`
* Format String (f-string)
* Membaca dan Menulis File (dengan *context manager* `with open()`)

---

## 🧠 Contoh Program Dasar

```python
# Contoh program Python sederhana
# (Tidak perlu include header seperti C++, langsung tulis kode)

def hitung_penjumlahan(a, b):
    # Fungsi untuk menjumlahkan dua bilangan
    return a + b

# Main block
nama = "Python"
a = 10
b = 7

print(f"Halo, Selamat datang di dunia {nama}!")

hasil = hitung_penjumlahan(a, b)

# Menggunakan f-string untuk output yang lebih bersih
print(f"Hasil penjumlahan {a} dan {b} adalah: {hasil}")
