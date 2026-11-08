# 📘 Catatan Belajar C — Sesi 1: Fondasi & Hello World

Tanggal:08/11/2026
Topik: Setup, Struktur Dasar Program C, Compile vs Runtime Error
Status:✅ Lulus (Program berhasil dijalankan)

---

## 1. Kode Program Pertama
Ini adalah kode yang pertama kali berhasil saya jalankan:
#include <stdio.h>

int main(void) {
    printf("Halo, namaku Zhafran\n");
    printf("Aku sedang belajar C\n");
    printf("Hari ini hari pertama\n");
    return 0;
}


## 2. Bedah Kode: Kenapa Ada Baris Ini?
Setiap baris punya alasan. Jangan asal hafal!

*   **`#include <stdio.h>`** 
    *   **Kenapa:** Ini seperti mengambil "kunci gudang". Tanpa ini, komputer tidak kenal perintah `printf`.
    *   **Untuk apa:** Memberi tahu compiler bahwa kita mau pakai alat dari library standar C (Standard Input/Output).
*   **`int main(void)`**
    *   **Kenapa:** Ini adalah pintu masuk utama (pintu depan) program. Komputer butuh tahu dari mana mulai membaca kodemu.
    *   **Untuk apa:** Tempat mengeksekusi semua instruksi. `int` berarti program akan melaporkan angka (exit code) saat selesai.
*   **`{ ... }` (Kurung Kurawal)**
    *   **Kenapa:** Sebagai pagar/isi rumah.
    *   **Untuk apa:** Menandakan area kode milik fungsi `main`.
*   **`printf("...\n");`**
    *   **Kenapa:** Perintah untuk mencetak teks ke layar. `\n` adalah kode untuk "Enter" (pindah baris). `;` (titik koma) wajib ada di setiap akhir perintah.
    *   **Untuk apa:** Menampilkan output ke pengguna.
*   **`return 0;`**
    *   **Kenapa:** Laporan ke komputer bahwa program selesai dengan sukses.
    *   **Untuk apa:** `0` berarti sukses. Kalau ada masalah, nilainya selain 0.

---

## 3. Dua Jenis Error (Penting!)
Ini fondasi untuk *debugging* (mencari kesalahan):

1.  **Compile-Time Error (Salah Sebelum Jalan)**
    *   **Penyebab:** Kesalahan penulisan/aturan (syntax), misalnya lupa titik koma `;`.
    *   **Akibat:** Program **tidak jadi dibuat**. Compiler langsung marah dan menolak.
2.  **Runtime Error (Salah Saat Jalan)**
    *   **Penyebab:** Kode benar secara tulisan, tapi logikanya bermasalah (misal: bagi dengan nol).
    *   **Akibat:** Program jadi dibuat, tapi **crash** atau hasilnya aneh saat dijalankan.

---

## 4. Tips Code::Blocks (Tools yang Saya Pakai)
*   **Tombol F9** = *Build and Run* (Kompilasi lalu Jalankan). Ini tombol sakti!
*   Jangan cuma klik "Run" (panah hijau) kalau belum di-*Build*.
*   Pesan error bisa dilihat di tab **Build Log** di bagian bawah.

---

## 5. Kosakata (English)
*Wajib dihafal untuk sesi berikutnya.*

| No | English | Arti |
|----|---------|------|
| 1 | Statement | Pernyataan / instruksi |
| 2 | Syntax | Aturan penulisan |
| 3 | Compiler | Penerjemah kode |
| 4 | Execute | Menjalankan |
| 5 | Output | Keluaran / hasil |
| 6 | Variable | Wadah nilai |
| 7 | Declaration | Deklarasi / pernyataan |
| 8 | Error | Kesalahan |
| 9 | Function | Fungsi / alat |
| 10 | Return | Mengembalikan nilai |

---

## 6. Evaluasi Diri (Refleksi)
*   **Apa yang sudah dikuasai:** Bisa menulis program 3 baris dari nol, bisa compile dan run, paham analogi `#include` dan `;`.
*   **Apa yang masih lemah:** Masih lupa beberapa arti kosakata (*Syntax, Compiler, Variable, Function, Return*).
*   **Target Sesi 2:** Belajar Variabel (`int`), memberi nilai (`=`), dan mencetak variabel pakai `%d`.

---
*Catatan ini dibuat untuk melacak progress belajar C dari dasar.* 🚀
