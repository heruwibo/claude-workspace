# Review Z1 - audit MoM dan relasi konteks (merged.txt)

## (a) MoM 17 butir (semua terpenuhi di dokumen gabungan)
| # | Lokasi di merged | Status |
|---|---|---|
| 1 | Bagian 1.4, setelah (a): Heading3 "Hubungan dengan organ lain", Tabel 2 RASCI 16 organ x 6 kelompok, 4 butir dasar tupoksi/uraian jabatan/akuntabilitas/KPI; baris keputusan baru; 13.6 merujuk balik | OK |
| 2 | 4.1: Heading3 "Parameter dan kondisi keberhasilan", Tabel 7, daftar kondisi pengakuan | OK |
| 3 | Tabel 10 (lama 8): baris "Industri pertahanan" NR + catatan opsi alternatif | OK |
| 4 | Gambar 2, Tabel 10, Tabel 11 lama dihapus dari 4.6; tidak ada rujukan menggantung | OK |
| 5 | 5.4: Tabel 19 definisi kolom + Tabel 20 peta, rujuk D2 | OK (pembacaan: "hlm. 26" = peta 5.4) |
| 6 | 5.7 "Skenario yang dipakai" + Tabel 21 sebelum Tabel 22-24; Tabel 25 (kerja) dirujuk | OK |
| 7 | 5.7 "Dua metode, satu rentang" Tabel 27-28 | OK |
| 8 | Gambar 6 siklus DOCK-UP (6.4) | OK |
| 9 | Gambar 5 kuadran TRL-MRL (6.3) | OK |
| 10 | 6.6 Barata, Tabel 32, label kelas C | OK |
| 11 | KKIP: 0 kemunculan (grep) termasuk glosarium | OK |
| 12 | Bab 6 diedit ulang (agen D1) | OK |
| 13 | 7.5 PELNI Rp4,5 T PMN, Tabel 36-37 | OK |
| 14 | 7.1 definisi + Tabel 33 kriteria; dirujuk Bab 1, 5, 6.10 | OK |
| 15 | 9.1 Prolog + Tabel 51 | OK |
| 16 | 8.9 Gambar 9 + Tabel 44-46 | OK |
| 17 | "Tim yang dibentuk oleh Wakil Ketua Danantara": sampul, pemberitahuan, 2.1, 8.9; 13.8 membedakan dari Wakil Kepala | OK |

## (b) Perbaikan yang dibuat (patch_Z1.py)
- 1.1 para pertama: +1 kalimat penunjuk ke Bagian 4.1 (parameter/peringkat) dan 4.4 (pertahanan NR).
- 1.1 butir makro: "11,4 juta tahun-kerja dan sekitar satu juta pekerjaan tetap" menjadi "9,4-11,4 juta tahun-kerja dan 976 ribu-1,24 juta pekerjaan tetap (rentang dua metode)". Tabel 1 temuan 8 disamakan.
- 1.1 butir NRF: "sebagian besar rentang toleransi" menjadi "hingga seluruh rentang" (sesuai 8.9: 0,1-1,0 poin); +1 kalimat merujuk Gambar 9 (model inflasi).
- 1.3 sel "Bangun": +1 kalimat contoh aktual Barata (6.6) dan PELNI (7.5), kelas C.
- 5.7 paragraf "Secara keseluruhan...": 11,4 juta diberi label ujung atas rentang.
- 16.1 alur kerja 1: pengesahan RASCI pada Hari ke-90 (sejalan dengan Bagian 1.4).
- Tahap menjadi Fase untuk PALCapital/AI: 1.4 ("PALCapital Fase 1"), 1.5 ("Fase 2 berjalan"), Tabel 3 baris D6, Lampiran B butir 18. "Tahap" dipertahankan untuk NRF (Tahap 0-3) dan pesanan DOCK-UP (Tahap 1-3).
- Lampiran C: baris perhitungan PELNI (4.500/16.500 = US$273 juta; Rp450 miliar per 10 poin). Lampiran D: entri "Proyek jangkar" dan "Sovereignty Project". Zebra tabel disusun ulang.

## (c) Diperiksa dan konsisten / tidak diubah
- Semua rujukan "Bagian x.y" (200+) menunjuk judul yang ada dan benar; semua "Tabel N/Gambar N" menunjuk objek yang dimaksud setelah renumber (termasuk 66/67, 52/53, 39, 43, 45, 25/26).
- Judul DOKUMEN-TOC cocok dengan judul bab; nomor halaman TOC basi (butuh pembaruan field di Word).
- RASCI 1.4 vs 13.6: kode A/R per kelompok cocok dengan matriks S01-S24; baris Kemhan/Kemenkeu/regulator/auditor eksternal diberi tanda usulan baru.
- Wakil Ketua (Danantara) vs Wakil Kepala (Badan Pelaksana) dibedakan eksplisit di 13.8.

## (d) Tidak diubah, perlu keputusan
1. Istilah "surat utang proyek" (Bab 1, 10, risiko) vs "Surat Tagihan Sovereignty Project" (9.6, Bab 16/17): dibiarkan; D6 menyebut surat utang berimbal hasil, 9.6 memberi nama keluarga. Sarankan satu kalimat penyamaan di 9.6.
2. UMKM (Tabel 18, 20, 6.1 sumber) vs UKM (Bab 6 dst): 6.1 sudah menjelaskan; dibiarkan.
3. Tabel tanpa judul (Bab 4, 6, 8, 13-17) tetap sesuai gaya baseline.
4. Tabel 35 dan 38 berjudul "Tangga pembiayaan" padahal isi gerbang proyek/lokalisasi (baseline).
5. 14.7 Tabel 70 "menurut D13" untuk jalur pengangguran 4,0-4,4% sedangkan 5.7 menyebut D11 pada kasus serupa; periksa sumber.
6. Z0 (3 Juta Rumah) dijalankan sebelum patch ini; merged.txt lama masih "5 Juta Rumah".
