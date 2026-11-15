# 📘 Catatan Belajar C — Sesi 4: Percabangan (if-else)

## 1. Apa itu Percabangan?
Percabangan membuat program bisa mengambil keputusan. Program tidak lagi berjalan lurus, tapi bisa memilih jalan berdasarkan suatu kondisi. Kita menggunakan `if` (jika), `else if` (jika tidak, lalu jika...), dan `else` (jika tidak).

## 2. Bedanya `=` dan `==` (SANGAT PENTING)
- `=` (satu) artinya **Assign** (Memasukkan nilai). Contoh: `umur = 20;`
- `==` (dua) artinya **Equal** (Membandingkan). Contoh: `if (umur == 20)`

## 3. Operator Pembanding
- `>` : Lebih besar dari
- `<` : Lebih kecil dari
- `>=` : Lebih besar atau sama dengan
- `<=` : Lebih kecil atau sama dengan
- `==` : Sama dengan
- `!=` : Tidak sama dengan

## 4. Contoh Kode: Cek Umur
```c
#include <stdio.h>

int main(void) {
    int umur;
    
    printf("Masukkan umur: ");
    scanf("%d", &umur);
    
    if (umur >= 18) {
        printf("Kamu sudah dewasa.\n");
    } else {
        printf("Kamu masih anak-anak.\n");
    }
    
    return 0;
}
