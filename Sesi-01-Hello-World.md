📘 Catatan Belajar C — Sesi 1
Topik: Pengenalan & Hello World
Status: Lulus

1. Kode Program Pertama
#include <stdio.h>

int main(void) {
printf("Halo, namaku Zhafran\n");
printf("Aku sedang belajar C\n");
printf("Hari ini hari pertama\n");
return 0;
}

2. Bedah Kode: Kenapa Ada Baris Ini?
#include <stdio.h> : Kunci gudang agar komputer kenal perintah printf.

int main(void) : Pintu masuk utama program. Komputer mulai membaca dari sini.

{ ... } : Pagar area program.

printf("...\n"); : Mencetak teks ke layar. \n artinya Enter. Wajib diakhiri titik koma ;.

return 0; : Laporan ke komputer bahwa program sukses (0 = sukses).

3. Dua Jenis Error
Compile-Time Error: Salah ketik/aturan (misal: lupa titik koma). Program tidak jadi dibuat.

Runtime Error: Kode benar, tapi logikanya salah (misal: bagi 0). Program jadi, tapi crash.

4. Tips Code::Blocks
Selalu tekan F9 (Build and Run) untuk menjalankan program.

Jangan cuma klik Run kalau belum di-Build.

Cek error di tab Build Log di bawah layar.

5. Kosakata English
Statement = Pernyataan/instruksi

Syntax = Aturan penulisan

Compiler = Penerjemah kode

Execute = Menjalankan

Output = Keluaran/hasil

Variable = Wadah nilai

Declaration = Deklarasi/pernyataan

Error = Kesalahan

Function = Fungsi/alat

Return = Mengembalikan nilai

Catatan ini dibuat untuk melacak progress belajar C dari dasar.
