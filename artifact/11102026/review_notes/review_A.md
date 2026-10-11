# Review A (front matter, Bab 1-3) - patch_A.py (tested with merge.py, no WARN)

## (a) MoM items
| Item | Location | Handling |
|---|---|---|
| 1 | Bagian 1.4, after the 1.4(a) table (before 1.4(b)) | New unnumbered Heading3 "Hubungan dengan organ lain: ringkasan matriks RASCI (usulan untuk dibahas)": statement that the relationship model with other organs is not yet modelled; list of organs (derived from Bab 3, Bab 13, D2); new summary table "Ringkasan RASCI organ x kelompok keputusan" (16 organs x 6 decision groups, built from the 24-activity RASCI of Bagian 13.6; activity groups listed in the source line; A cells carry the S-codes); bullets stating the RASCI is the basis for tupoksi, uraian jabatan, akuntabilitas, KPI (Bab 14). All letters labelled usulan; refers to "Bagian 13.6". Also added 1 decision row to 1.4(a) ("Mengesahkan matriks RASCI ...", Hari ke-90, usulan) and a sentence in the 1.3 "Tata kelola" cell. |
| 11 | 1.4(a) row 3; 1.4(b) row 4 | "KKIP" removed (now Kementerian Pertahanan only). No other KKIP in my scope. |
| 14 | 1.2 finding 4 | Parenthetical at first use: "proyek jangkar (anchor project: proyek berdampak besar dengan rantai pasok panjang; definisi dan kriteria pada Bagian 7.1)". Bab 2/3 do not contradict (2.2 Q3 only uses the term). |
| 17 | Cover, Pemberitahuan penting, 2.1 | See (d). Removed "Danantara Danantara" (cover) and "(Steering Committee) Danantara" (notice, 2.1); 2.1 "salah satu anggota Tim" -> "anggota Tim" (as cover/notice). |
| notice | after "Pembaruan 8 Oktober 2026" | New short paragraph "Pembaruan berdasarkan risalah rapat pembahasan (9 Oktober 2026)". 2.3 got one added sentence (MoM-only material = kelas C, not a D-source); 2.5 got one bullet (MoM input unverified; RASCI for external parties = analyst proposal). Tabel 2 (register sumber) unchanged. |
| TOC | Daftar isi | Chapter/Lampiran titles checked against the actual headings: all match. Page numbers stale, left untouched (cannot be recomputed). If another agent renames a chapter, TOC must be updated manually. |

## (b) Fixes
- Cover: "Wakil Ketua Danantara Danantara" -> "Wakil Ketua Danantara".
- Notice, 2.1: "(Steering Committee) Danantara" deleted.
- 1.1 bullets: merged "...mengintegrasikan portofolio. Unit ini menjalankan konsep NITO;" into one sentence; bullet end punctuation ("." -> ";" on NRF bullet and BUMN Karya bullet).
- 1.2 finding 4: garbled "...ofset paling sedikit 85%, termasuk ... paling sedikit 35%" -> "paling sedikit 35%, yang naik 10 poin setiap 5 tahun hingga 85% (UU 16/2012, Pasal 43) [D4]" (D4 infographic: "85% / 35% ... naik 10 poin setiap 5 tahun").
- "risiko fiscal" -> "fiskal" (1.4b); "layanan public" -> "publik" (3.2); "secara independent" -> "independen" (2.4 and Tabel 18 Inovasi row in Bab 5, via replace_everywhere); "biaya-biaya dan" -> "biaya dan" (Tabel 3).
- 3.7: "PP 34/2025" (D9) flagged "[perlu diverifikasi: D2 merujuk PP 10/2025 dan PP 19/2026]".
- Table widths in scope all sum to 9638. Captions renumber automatically (new table = Tabel 2).

## (c) CROSS-SCOPE / not fixed
- Lampiran D glosarium still has "KKIP" row; Bab 6 (idx ~401, 409, 417 and a table cell "Anggaran program Danantara / KKIP") and Bab 17 ("Untuk pertimbangan Kementerian Pertahanan dan KKIP") use KKIP: owners must remove.
- Bab 13 (agent G): add cross-reference to the 1.4 summary table in Bagian 13.6; if RASCI codes/activities change there (S01-S24 numbering, A-owners), the 1.4 summary table must be re-derived (groups: 1=S01-S03,S09; 2=S04,S05,S08; 3=S10-S13,S24; 4=S14-S16,S19,S20; 5=S06,S07,S22; 6=S17,S18,S21,S23).
- Bab 8 (idx ~570/1119 region) uses "Tim yang dibentuk oleh Wakil Ketua Danantara" and "laporan triwulanan public" (typo -> publik).
- Bab 1 executive summary (1.1-1.3) will need a one-line update after merge if: Bab 4 success parameters are reworded; Tabel 8 gets the pertahanan row (NR) - the "lima temuan"/1.1 text says sectors are not assessed; DOCK-UP examples (Barata V-Bracket, kelas C) and the PELNI Rp4,5 T PMN anchor example are added (1.3 "Bangun" row, 1.2 finding 4); inflation model (item 16) - the 1.1 inflation bullet references Bagian 8.9 only. 1.1 "Rp1.486,5 triliun" etc. unchanged.
- Tabel in 2.2, 2.4, 3.1-3.3 etc. have no captions while later tables do (pre-existing style; not changed to avoid renumbering).
- D9's PP 34/2025 is not listed in Lampiran B (suggest adding as a discrepancy).
- Bab 1 text "ketiga aliran" / numbering of references "Bagian 6.9" - verified existing.

## (d) Assumptions for client confirmation
- Item 17 interpretation: the MoM line is terse; I read it as "the document must consistently identify itself as prepared by the Tim yang dibentuk oleh Wakil Ketua Danantara". The name is kept exactly as the client wrote it. "Wakil Ketua Danantara" is NOT a term in D2 (D2 uses Kepala Badan Pelaksana, Wakil Kepala Badan Pelaksana as an option, and Wakil Ketua Dewan Pengawas); I did not equate them. "(Steering Committee)" was removed because it read as a label for the Wakil Ketua/Tim and was not defined; if the Tim is in fact the Steering Committee, restore as "Tim yang dibentuk oleh Wakil Ketua Danantara (Steering Committee)". Please confirm whether "Wakil Ketua" means Wakil Ketua Dewan Pengawas or another post.
- Authorship: "anggota Tim" used uniformly (cover, notice, 2.1); 1.4 uses "Kami/penulis" elsewhere.
- Date "9 Oktober 2026" for the MoM taken from the sources folder and the task note.
- RASCI summary: rows for Kementerian Pertahanan, Kementerian Keuangan, regulator, auditor eksternal (marked *) are my proposals (not in D2/13.6); letters of other rows are condensed from 13.6 ("peran terkuat dalam kelompok"). The 1.4(a) new decision row and its "Hari ke-90" timing are usulan.
