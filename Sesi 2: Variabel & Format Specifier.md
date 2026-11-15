# 📘 Catatan Belajar C — Sesi 2

| 📚 Topik | 📌 Status | 🎯 Pencapaian |
| :--- | :--- | :--- |
| Variabel & Format Specifier (`%d`) | ✅ Lulus | Fondasi variabel sudah dikuasai! 🚀 |

---

## 📦 1. Apa itu Variabel?

Variabel adalah **"wadah"** atau **"toples"** untuk menyimpan nilai di dalam memori komputer.
* **Contoh penulisan:** `int umur = 20;`

| Potongan Kode | Fungsi & Penjelasan |
| :--- | :--- |
| **`int`** | Tipe data bilangan bulat (*Integer*). |
| **`umur`** | Nama variabel (bebas, tidak boleh memakai spasi). |
| **`=`** | Tanda *Assign* (memberi atau memasukkan nilai ke wadah). |
| **`20`** | *Value* (nilai asli yang disimpan di dalam variabel). |

---

## 🎯 2. Format Specifier (`%d`)

Untuk mencetak isi variabel angka bulat ke layar, kita menggunakan **`%d`** (singkatan dari *decimal*).
* **Contoh penulisan:** `printf("Umur saya %d tahun\n", umur);`

* **`%d`** berperan sebagai **"lubang" kosong** di dalam teks.
* **`umur`** di ujung kanan (dipisah tanda koma) adalah **isi nilai** yang akan dimasukkan ke lubang tersebut.

---

## 🧮 3. Operasi Aritmatika Dasar

Kita bisa melakukan perhitungan matematika secara langsung menggunakan variabel (contoh: `int hasil = a + b;`):

| Operasi | Simbol Operator | Contoh Penggunaan |
| :--- | :---: | :--- |
| **Tambah** | `+` | `a + b` |
| **Kurang** | `-` | `a - b` |
| **Kali** | `*` | `a * b` |
| **Bagi** | `/` | `a / b` |

---

## 💻 4. Kode Program Latihan
```c
#include <stdio.h>

int main(void) {
    // --- LATIHAN 1: Menghitung Umur ---
    int tahun_lahir = 2008;
    int tahun_sekarang = 2026;
    int umur = tahun_sekarang - tahun_lahir;
    printf("Umur saya saat ini adalah %d tahun\n", umur);

    // --- LATIHAN 2: Penjumlahan ---
    int a = 15;
    int b = 4;
    int hasil = a + b;
    printf("Hasil dari %d + %d adalah %d\n", a, b, hasil);

    return 0;
}
```

---

## 📚 5. Kosakata Bahasa Inggris (Pemrograman)

| No | Istilah | Arti / Makna |
| :---: | :--- | :--- |
| 1 | **Assign** | Memberi nilai |
| 2 | **Value** | Nilai |
| 3 | **Integer** | Bilangan bulat |
| 4 | **Format Specifier** | Penentu format (seperti `%d`) |
| 5 | **Initialize** | Mengisi nilai awal |
| 6 | **Subtract** | Mengurangi |
| 7 | **Add** | Menambah |
| 8 | **Result** | Hasil |
| 9 | **Variable** | Wadah nilai |
| 10 | **Compiler** | Penerjemah kode |
