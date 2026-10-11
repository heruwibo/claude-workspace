# Review E2 – Bab 9 dan Bab 10

Patch: `work/patch_E2.py` (merge.py: no WARN). Figure: `work/figs/E2_pal_tranche.png`.

## (a) MoM items
- **Item 15** (9.1, "halaman 53" read as Bagian 9.1): after the 9.1 heading, new Heading3 "Prolog: dari konsep Sovereignty Project ke contoh yang dikaji" with 3 paragraphs (definition; why tokenisation fits; cases examined + relation to NRF/Bab 10.2) and a new table "Contoh yang dikaji dan letak analisisnya" (PAL-SUB-1 -> 9.2-9.6; Barata V-Bracket -> 6.6; PELNI Rp4,5 T PMN -> 7.5), then Heading3 "Masalah yang ditangani PT PAL" before the original text. The doc had no definition of "Sovereignty Project": the definition is a working definition (kelas D), derived from the Bagian 9.6 design rules and D6 ("secured sovereign receivable"). Barata/PELNI rows are labelled "(kelas C; masukan rapat pembahasan)" and only point to 6.6 / 7.5. I add (labelled usulan) that PMN is equity, not a contractual receivable, so applicability of tokenisation to PELNI must be tested against 9.6.
- **Item 11 (KKIP)**: no occurrence of KKIP in Bab 9 or 10 (checked dump); nothing to remove. Kemhan/Kemenkeu logic in 9.2/9.5 unchanged. KKIP remains elsewhere (Bab 3/6 task tables, 6.x, glossary line ~2097, summary ~1882): other agents.

## (b) Fixes
- Gambar 8 redrawn: x-axis labels "T1 Pemotongan baja"/"T2 Peletakan lunas" overlapped; new PNG (two-line labels, same palette). Added lead-in sentence in 9.3 that cites Gambar 8 (it was never referenced) and the 6-step flow.
- New captions + source lines (tables had none): fitur PAL-SUB-1 (9.2), Tabel 39 source, aturan desain (9.6), Tabel 40 source, 10.2 comparison, 10.4 two ladders, 10.6 stress tests. Numbers re-assigned by merge.py (Tabel 39->43 etc.).
- Tabel 41 and Tabel 42 captions were separated from their tables by an intro paragraph: moved directly above table. Removed stray empty paragraphs before/after tables where a source line was added. Tabel 41 source got "Sumber: perhitungan kami dari D3, D5, dan D6".
- 9.5: added mapping paragraph (6 prasyarat -> 10 isu in Tabel 39; teknologi -> kontrol platform + risiko 8 Bab 15). Callout "pengalihan dan pengalihan arah pembayaran" -> "pengalihan tagihan dan pengalihan arah pembayaran".
- 9.6 table: "skema KPBU" -> "skema kerja sama pemerintah dengan badan usaha (KPBU)" (first expansion in Bab 9).
- 10.3: "secara umum setara dengan ... alokasi strategis + jendela industri NRF" was not arithmetically true (Rp627 T vs 578+118 = 696 T). Reworded: lebih besar dari Rp578 T, sebanding dengan gabungan 578+118 (Rp696 T).
- 10.7: "risiko 9, 15, dan 16" -> "9, 15, 16, dan 24" (risk 24 in Bab 15 is the bank-BUMN greenfield risk this section is about).
- Tabel 43 note: "Rp2.091 T per enam tahun" now says 2027-2032 in D11 (6 years) vs 5-year horizon in 10.3 (was unexplained).
- Verified arithmetic: Tabel 41 (578, 118, 83, 24, 142, 6,8%, 27,6%, 1.371, 65,6%), 627/1.464, 419/2.091, Tabel 42 NPV/IRR, 700 bps x 720/365 = 20,7, 10,4; PAL data vs D6 (tranche 40/45/40/25 = 150, 3-of-5, 3-day timelock, 15% DP). All OK.

## (c) Not fixed / cross-scope
- Terms mixed: "Surat Tagihan Sovereignty Project" (9.6, 10.x) vs "surat utang proyek" (Bab 1, 10.3, risk register). Left; suggest harmonising in Bab 1/8.
- Bab 1 / Bab 16 wording "keenam prasyarat tersertifikasi" (odd phrase); outside scope.
- 8.3 says "Delapan isu" and 9.4 ten issues: consistent; no action.
- Prolog references Bagian 6.6 and 7.5 for Barata/PELNI: must exist after D1/D2 patches (6.6 heading "6.6 Dua jalur melalui DOCK-UP", 7.5 "Contoh penerapan: proyek jangkar maritim" unchanged in baseline). If D1/D2 rename them, update.
- 10.2 flow diagram table and 9.3 flow table are untitled tables (kept as diagrams).

## (d) Assumptions needing client confirmation
- "Sovereignty Project" definition (working definition, kelas D).
- Reading of "halaman 53" = Bagian 9.1.
- Mapping of 6 prasyarat to 10 isu (our own).
- Statement that PMN (PELNI) is equity and tokenisation applicability is to be tested.
