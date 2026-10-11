# Review B – Bab 4 Evaluasi kinerja (patch_B.py)

## (a) Butir MoM
| Butir | Lokasi | Tindakan |
|---|---|---|
| 2 | Bagian 4.1, setelah paragraf "Kesimpulan terkuat…" | Heading3 baru "Parameter dan kondisi keberhasilan Danantara: cara membaca penilaian": pengantar; 3 butir (yang dinilai, parameter, ambang); tabel baru "Cara membaca skala peringkat dan skor konservatif" (Terbukti / Sebagian terbukti / Belum terbukti / NR / skor 0/100: artinya vs. tidak berarti); 5 butir kondisi pengakuan keberhasilan (dari kolom "Hal yang dapat menaikkan peringkat" dan penanda bulan ke-12/24 Bagian 1.5); paragraf penutup (belum dapat dinyatakan berhasil/gagal). Seluruhnya dari Bagian 1.5, 2.4, 2.5, 14.1, Tabel 6, 13 dan D7; tidak ada ambang baru. |
| 3 | Tabel 8 (kini Tabel 9) | Baris "Industri pertahanan" (NR) disisipkan setelah "Manufaktur maju"; zebra diperbarui; sumber diperluas (D3, D4, D6, D8); kalimat pengantar 4.4 menyebut penambahan; catatan penjelas di bawah tabel. Tidak ada kalimat di Bab 4/Bab 1 yang menghitung jumlah sektor ("sembilan sektor" dsb.), jadi tidak ada koreksi hitungan. |
| 4 | Bagian 4.6 | Gambar 2, Tabel 10, Tabel 11 (judul, gambar/tabel, baris sumber) dihapus. Dua paragraf disusun ulang agar angka kuncinya tetap ada tanpa tabel: paragraf pembuka (menambahkan fakta 5 slot Mineral dan 3 slot pertahanan sudah bernama, dari Tabel 10 lama) dan paragraf "Beberapa angka total…" (headline 2.091,46; selisih 18,93; 604,97 = 28,9%; 1.486,49; 695,72; rujukan Lampiran C). Gambar 1, Tabel 12 dst. tetap. Grep seluruh dump: tidak ada rujukan lain ke Gambar 2/Tabel 10/Tabel 11 selain keterangan sendiri. |
| 11 | Bab 4 | Tidak ada "KKIP" di Bab 4 (dump idx 162-252). Kemunculan di luar lingkup lihat (c). |

## (b) Perbaikan format/penulisan
- Tabel 7 lama, sel "PLN (Persero) (perusahaan listrik negara)" menjadi "PLN (Persero), perusahaan listrik negara" (tanda kurung ganda).
- Paragraf pengantar Tabel pencocokan D7: "yoy" menjadi "secara tahunan" (campur bahasa).
- Lebar kolom semua tabel Bab 4 dicek: seluruhnya berjumlah 9638.

## (c) Di luar lingkup / tidak diperbaiki
- CROSS-SCOPE KKIP: Bagian 1.4 (tabel keputusan, baris "berkoordinasi dengan KKIP…" dan "Kementerian Pertahanan dan KKIP"), Bab 6.9 (butir "dikoordinasikan oleh KKIP (Komite Kebijakan…)", paragraf "KKIP menetapkan kebijakan industri pertahanan", sel "Anggaran program Danantara / KKIP", paragraf biaya "integrator dan KKIP"), Bab 8/10 kutipan "Untuk pertimbangan Kementerian Pertahanan dan KKIP" (ringkasan keputusan, dump ~1882), Lampiran singkatan "KKIP".
- CROSS-SCOPE: Gambar 2/Tabel 10/11 tidak dirujuk di luar Bab 4. Nomor Gambar/Tabel setelahnya bergeser otomatis (Tabel 12 menjadi 11, dst.; ditambah 1 tabel baru di 4.1 sehingga Tabel 6 baru; Tabel 6 lama menjadi 7). Rujukan klien ke "Tabel 19", "Tabel 25" pada MoM mengacu penomoran lama.
- Tabel tanpa judul/nomor di Bab 4 (tabel peringkat 4.1, tabel organ 4.5, tabel enam dimensi 4.6) tidak diberi judul karena akan menggeser penomoran seluruh dokumen; disarankan dibiarkan.
- Inkonsistensi substantif untuk klien: skor D7 "0" untuk metrik tanpa data bertentangan dengan aturan Bagian 14.1 ("tetap NR, tidak pernah nol"). Dijelaskan di tabel 4.1 sebagai konvensi penalti D7; Bagian 14.1 dan Bab 1 (poin 1 pembaruan) bisa diberi catatan serupa (lingkup lain).
- Gambar 1 sumber menyebut "(U1)" tanpa penjelasan; tidak diubah (tidak ada definisi di dump).

## (d) Interpretasi / asumsi untuk konfirmasi klien
- "Opsi kedua dibuat sebagai catatan penjelas" saya baca: opsi pertama = baris sektor pertahanan bernilai NR di tabel; opsi kedua = tidak membuat baris sendiri (menggabungkan dengan "Manufaktur maju") atau menilai setelah ada bukti, dan opsi ini hanya dijelaskan dalam catatan di bawah tabel, bukan diterapkan.
- Definisi "Sebagian terbukti" dan "Terbukti" pada tabel baru adalah pembacaan kajian atas skala di Bagian 4.1 (sumber tidak mendefinisikannya eksplisit); diberi label interpretasi pada baris sumber.
- Kegiatan pertahanan pada baris tabel: DOCK-UP dan PALCapital dinyatakan "masih berupa usulan" sesuai dokumen; "Rp24,36 T (3 slot)" dari D8 dan "Rp81,10 T" dari ringkasan D8 (memakai angka yang sama dengan Tabel 10 lama).
- Kondisi pengakuan keberhasilan bulan ke-12/24 adalah penanda usulan Bagian 1.5, bukan target tetap.
