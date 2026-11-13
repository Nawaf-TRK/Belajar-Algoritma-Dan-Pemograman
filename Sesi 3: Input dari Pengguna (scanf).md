# 📘 Catatan Belajar C — Sesi 3: Input dari Pengguna (scanf)

## 1. Apa itu scanf?
Kalau `printf` adalah alat untuk mengeluarkan teks (Output), maka `scanf` adalah alat untuk memasukkan data dari keyboard ke dalam variabel (Input).

## 2. Aturan Wajib scanf: Tanda & (Ampersand)
Berbeda dengan printf, saat menggunakan scanf kita WAJIB menambahkan tanda `&` di depan nama variabel.
Contoh: `scanf("%d", &umur);`

- Tanda `&` berarti "Alamat" (Address).
- Fungsinya memberitahu komputer: "Tolong simpan ketikan pengguna ke lokasi wadah (variabel) yang ada di memori ini."
- Tanpa tanda `&`, program akan crash.

## 3. Contoh Kode Interaktif (Hitung Umur)
```c
#include <stdio.h>

int main(void) {
    int tahun_lahir;
    int tahun_sekarang = 2026;
    int umur;

    printf("Masukkan tahun lahir kamu: ");
    scanf("%d", &tahun_lahir);

    umur = tahun_sekarang - tahun_lahir;

    printf("Umur kamu saat ini adalah %d tahun\n", umur);

    return 0;
}
4. Kosakata Baru
Input: Masukan
Prompt: Teks ajakan di layar
Address: Alamat memori
Ampersand: Simbol &
Calculate: Menghitung
User: Pengguna
Interactive: Interaktif
Sum: Jumlah
Integer: Bilangan bulat
Format Specifier: Penentu format
