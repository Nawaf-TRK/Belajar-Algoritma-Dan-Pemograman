# 📘 Catatan Belajar C — Sesi 1

| 📚 Topik | 📌 Status | 🎯 Tujuan |
| :--- | :--- | :--- |
| Pengenalan & Hello World | ✅ Lulus | Melacak *progress* belajar bahasa C dari dasar |

---

## 💻 1. Kode Program Pertama
```c
#include <stdio.h>

int main(void) {
    printf("Halo, namaku Nawaf\n");
    printf("Aku sedang belajar C\n");
    printf("Hari ini hari pertama\n");
    return 0;
}
```


---

## 🔍 2. Bedah Kode: Kenapa Ada Baris Ini?

| Potongan Kode | Fungsi & Analogi Sederhana |
| :--- | :--- |
| **`#include <stdio.h>`** | **Kunci gudang** agar komputer mengenali perintah input/output seperti `printf`. |
| **`int main(void)`** | **Pintu masuk utama** program. Komputer selalu mulai membaca kode dari titik ini. |
| **`{ ... }`** | **Pagar area** yang menandai awal dan akhir blok isi program. |
| **`printf("...\n");`** | Mencetak teks ke layar. `\n` berfungsi sebagai tombol **Enter** (baris baru). Wajib diakhiri titik koma (`;`). |
| **`return 0;`** | **Laporan status** ke sistem operasi bahwa program selesai dijalankan dengan sukses (`0` = sukses). |

---

## ⚠️ 3. Dua Jenis Error di Bahasa C

* **Compile-Time Error:** Kesalahan pengetikan atau melanggar aturan penulisan bahasa C (misalnya lupa tanda titik koma `;`). Akibatnya, program gagal dikompilasi dan file aplikasi tidak terbuat.
* **Runtime Error:** Penulisan kode sudah benar, tetapi terjadi kesalahan logika saat dijalankan (misalnya membagi angka dengan `0`). Program berhasil dibuat, tetapi mengalami *crash* saat berjalan.

---

## 🛠️ 4. Tips Menggunakan Code::Blocks

* Selalu tekan tombol **`F9` (Build and Run)** setiap kali ingin menjalankan program terbaru.
* Hindari menekan tombol *Run* saja jika kode baru saja diubah dan belum di-*Build*.
* Jika terjadi kegagalan, periksa detail pesan kesalahannya pada tab **Build Log** di bagian bawah layar.

---

## 📚 5. Kosakata Bahasa Inggris (Pemrograman)

| No | Istilah | Arti / Makna |
| :---: | :--- | :--- |
| 1 | **Statement** | Pernyataan / instruksi |
| 2 | **Syntax** | Aturan penulisan kode |
| 3 | **Compiler** | Penerjemah kode ke bahasa mesin |
| 4 | **Execute** | Menjalankan program |
| 5 | **Output** | Keluaran / hasil |
| 6 | **Variable** | Wadah penyimpan nilai |
| 7 | **Declaration** | Deklarasi / pernyataan pengenalan |
| 8 | **Error** | Kesalahan |
| 9 | **Function** | Fungsi / blok alat kerja |
| 10 | **Return** | Mengembalikan nilai |
