# review_Z2 – QA format + proofreading (merged doc)

Test: `merge.py base.docx out_Z.docx patch_A..G, Z0, Z2` -> applies cleanly, 0 `[[` tokens left, no dangling-ref WARN. (merged.docx predates Z0; checks re-run on out_Z.docx.)

## (a) Programmatic format audit
OK: all 70+ tables gridCol = tcW = 9638, uniform cell counts per table; header fill 00338D on all captioned tables; zebra EAF2FB alternation correct in all new tables; table font 16 (dense new tables 14/15 half-pt: Tabel 2 RASCI 7 kol = 15, Tabel 39/42/43/70 = 14-15, same as baseline dense tables); captions 18 bold 00338D, all with keepNext; sources 15 italic; no 2+ consecutive empty paragraphs in new content (6 hits = baseline banner spacers, also in base); no duplicate docPr ids; png Default content type present; all r:embed resolved; document.xml well-formed; bullets use numId 2 (new) – no stray ids.
Figures (12): width 8.1–16.3 cm (<=17), heights 5.7–11.9 cm after fix, alt text on all, caption above image on all, source below.
Heading3 without Heading2 parent: none.
Not fixed (baseline pattern, harmless): Tabel 56 body rows all shaded (baseline table); Tabel 71 has a legend paragraph between caption and table (baseline Tabel 53 pattern); ~25 old tables have no "Sumber" line directly below (baseline).

## (b) Proofreading – fixes in patch_Z2.py
| Where | Before -> After |
|---|---|
| Halaman judul, par. "Pembaruan…" | duplicated "risalah rapat pembahasan" sentence -> "Versi ini memperbarui versi 8 Oktober 2026 berdasarkan risalah rapat pembahasan (MoM) tanggal 9 Oktober 2026." |
| Lampiran singkatan/skor (TD) | "actual tidak ditemukan" -> "aktual" |
| Bagian 8.9 pembuka | "fiscal capture" -> "penarikan penerimaan fiskal (fiscal capture)" |
| Tabel 44/45 (lapis indikator, ambang) | "yoy, mtm" -> "tahunan, bulanan"; "IHK yoy"/"Volatile food yoy" -> "tahunan" |
| Tabel 46 + par. "Laju kontra-siklus" | "milestone" -> "tonggak capaian" (istilah dokumen) ; same word in Gambar 9 regenerated |
| Bagian 7.5 | "10 poin persen" -> "10 poin persentase" (konsisten dengan teks lain) |
| Bagian 8.9 | "sehingga, bila" -> "sehingga bila" |
| Bagian 4.1 (bullet "Ambang.") | last bullet ended ";" -> "." |
Scans with no hit in new text: duplicated words, double spaces, " ,", missing space after punctuation (hits are only multi-paragraph cells concatenated by the dump), "Rp 1", decimal point/thousand comma errors, "Rp.", "US$ 1". Number style (Rp1.486,5 T; decimal comma) consistent. Evidence-class labels consistent: "(kelas C; masukan rapat pembahasan)", "kelas D", "Kelas bukti D".
Left as is (baseline style, meaning-preserving not guaranteed): "di mana" as relative pronoun (6x), "persentase aktual", Kemenkeu/Kementerian Keuangan mix, "Infra­struktur" (soft hyphen) in Tabel 23 header, English technical terms (lead time, first-loss, off-taker) used throughout.

## (c) Figures
- Gambar 9 (E1 model): was 14 x 17.5 cm. Re-laid out (8 jalur in one row, 4+5 merged with colour-linked threshold -> response boxes): 14.5 x 11.9 cm, font >= 8 pt. Script fig_E1_model.py (old version .bak.py); patch_E1.py width_cm 14.0 -> 14.5.
- Gambar 5 (kuadran), 6 (siklus), 10 (tranche): legible, no overlap/clipping; no change.

## (d) Placeholders `[perlu diverifikasi…]` (22) – client must resolve
- Bagian 3.7 par. D9: D2 merujuk PP 10/2025 dan PP 19/2026 (vs PP 34/2025)
- Heading "Dua metode, satu rentang" (Bagian 5.7): penyebab selisih per klaster
- Bagian 6.6 Tabel 32 (Barata), 4 sel: baseline TRL/MRL & supervisi PAL; jumlah unit/pesanan/kontrak payung; lingkup sertifikasi (ISO 9001, 3834/9606); gerbang tertinggi, basis penurunan >50%, periode. Plus par. sumber (tanda umum) dan "Barata adalah BUMN manufaktur… status dan skala usaha"
- Bagian 7.1 Tabel 33 kriteria 2: [perlu keputusan Badan Pelaksana] ambang nilai investasi
- Bagian 7.5: par. pembuka (rincian lain), Tabel 36 (8 sel: unit penandatangan, jenis/jumlah kapal, nilai total vs pembangunan, dasar hukum PMN, galangan/klasifikasi, jadwal, target TKDN, kaitan slot SP-21), Tabel 37 (daftar material kapal; jadwal PMN), par. PMN (disalurkan langsung atau lewat Danantara)

## (e) Cross-scope notes for Z1
- Tabel 66/67: D3 4 GPU vs 4–8 GPU already flagged in the text; fine.
- Check "Tabel 53" references in Bagian 7.5/9.1 (point to Isu PALCapital) – correct after renumbering.
- Stale TOC page numbers (cannot be regenerated here).
