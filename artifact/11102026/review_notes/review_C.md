# Review C - Bab 5 "Apa yang diharapkan dari Danantara" (Bagian 5.1-5.7)
Patch: patch_C.py (tested with merge.py on baseline, no WARN). Output: out_C.docx / out_C.txt. No new figures.
Captions are given original numbers in this file; merge.py renumbers (new tables shift later numbers by up to +9 within Bab 5).

## (a) MoM items
| MoM | Where | What was done |
|---|---|---|
| 5 (hlm. 26) | 5.4, Heading3 "Satu peta dari proyek jangkar ke portofolio" | Reading: page 26 = 5.4. Treated the 8x5 mapping table (columns "Klaster (D2)", "Penanggung jawab kapabilitas/imbal hasil" not explained; D2 defines clusters and leader roles in sections 8-10). Added new table "Definisi kolom pada peta..." (5 columns defined, each with D2 section / Bagian reference), rewrote lead-in paragraph, added caption and source to the map table. Curated map: 7 rows to 6 (merged "Maritim" and "Program pertahanan", same cluster/portfolio/leader), shortened repeated wording, typo "klister" removed, last row marked "(lintas proyek)". Also added a "Cara membaca Tabel 18" paragraph (column meanings for Tabel 18, ref D2 section 10) and fixed "independent". Alternative candidate (Tabel 17/18) handled lightly only. |
| 6 | 5.7, new Heading3 "Skenario yang dipakai pada bagian ini", placed before "Metode dan parameter" (so before Tabel 19) | Intro paragraph (three scenario families: pipeline model cases, S1-S3, localisation scenarios of Tabel 17), comparison table "Skenario dan kasus yang dipakai pada Bagian 5.7" (8 rows: kasus dasar, KD rendah/tinggi, efisiensi IMF, jembatan 2029, S1, S2, S3, jalur D11; columns question / assumptions / where used) and a "Hubungan antarkelompok" paragraph (base case = reference for Tabel 20; jobs Tabel 22-23 same pipeline but bottom-up; S1-S3 do not re-run the pipeline model, pipeline enters as SDA lever +0,34 pp 2029; S2 doubles pipeline; the different ICOR values 6,5 / 5,6 / 5,0 / 5,6 to 5,1 / 3,95-4,8-4,3 not additive). All numbers from D11 Tabel 8.1, 8.5, 11.2, 12.1, Lampiran E and existing text. |
| 7 | 5.7, run-in paragraph "Dua metode, satu rentang." replaced by Heading3 "Dua metode, satu rentang" | Method comparison table (source, starting point, calculation, coverage, 9,4 vs 11,4 juta, 1.241 vs 976 ribu, strengths, limits); cluster-by-cluster comparison table (D11 Tabel 8.2 vs D13 / Tabel 22) showing the gap is concentrated in SDA (approx. 1,9 of 2,0 juta tahun-kerja) and that permanent jobs differ strongly per cluster (infra 842 vs 296 ribu) and offset in total; paragraph on how the range is formed (per indicator, not a confidence interval; lower bound comes from different methods for the two indicators); 4 bullets on which end to use for what (stakeholder reporting = full range; project analysis = bottom-up; conservative internal targets = lower end per indicator; sensitivity to multipliers = PDB-derived) - labelled "usulan kajian ini". Pointer to Lampiran B. Cross-links added in the Tabel 20 source line and in the "Lapangan kerja, proyek demi proyek" paragraph. |
| 11 KKIP | Bab 5 | No occurrence of KKIP in Bab 5 (checked). Occurrences elsewhere (Bab 6, 6.9 lines, 17, glossary) belong to other agents. |
| 14 fwd | 5.1 "Orde besaran" paragraph | First use of "proyek jangkar" in Bab 5 now carries "(proyek strategis dengan rantai pasok panjang dan dampak besar; kriteria pada Bagian 7.1)"; same wording used in the new column-definition table. Depends on agent D2 actually adding the criteria to 7.1. |

## (b) Other fixes
- 5.1 table header: "Ukuran utama (Bab 14; ...)" to "Ukuran utama (kode indikator pada Bab 14; ...)" (D01/D06 codes looked like sources D1/D6).
- 5.1 closing paragraph: "kemungkinan besar akan jauh melampaui biaya DOCK-UP" (unsupported, 6.9 says cost not estimated) to "tampaknya ... tetapi biaya itu belum diestimasi (Bagian 6.9)".
- Tabel 18 cell: "independent" to "independen".
- Tabel 20 (orig.) header "Infra-struktur" to soft-hyphen "Infra­struktur".
- Tabel 23 (orig.) source: dagger (†) was undefined, added "† Program rahasia (black programme) menurut D11".
- Tabel 25 (orig.): empty top-left header cell now "Indikator"; added two rows from D11 Tabel 12.1 (pertumbuhan investasi per tahun 8,9/15,3/11,6%; tambahan tabungan nasional +1,5/+6,0/+4,0 pp) so the financing assumption behind the current-account row is visible; zebra re-applied; source line notes the added rows. All other Tabel 25 values re-checked against D11 Tabel 12.1: consistent.
- Tabel 24 (orig.) source: ICOR 3,9 (31,2%) vs S1's 3,95 (31,5%) in Tabel 25 - D11 itself rounds; explained in the source line.
- Arithmetic re-checked: Tabel 17 (all cells reproduce from the stated assumptions), Tabel 22 rows/totals (rounding only), Tabel 23 ordering, 21% differences, 33,5 / 4,2.
- Numbers vs Bab 1 / Tabel 1 / Bab 15 / Lampiran B / 14.4 / 14.7: 1,5%, 0,74%, 11,4 juta, 976 ribu, US$38,8 miliar, Rp2.091 T, Rp419 T, 9,4 juta / 1,24 juta, ICOR 4,2: consistent. No change needed outside scope.

## (c) CROSS-SCOPE / not fixed
- Bab 1 / Executive summary (para "Manfaat makro besar...") quotes only 11,4 juta and "sekitar satu juta pekerjaan tetap"; consider adding "(rentang 9,4-11,4 juta)" for consistency with the new range logic. Owner: Bab 1 agent.
- "Proyek jangkar" is used in Bab 1-4 before its definition; 7.1 definition is by agent D2 - check my wording "rantai pasok panjang dan dampak besar" matches.
- 7.2 (Tabel with four clusters) and my column-definition table overlap in cluster names; keep names identical ("Energi dan infrastruktur industri", "Pertahanan dan maritim", ...). They currently match.
- Tabel 24 in Bab 14.7 / 15 mention "skenario D11" - consistent with S1-S3 naming.
- Lampiran B row 25 is consistent with the new range text; no change.
- 5.1 first table, 5.2 value table, 5.3 flow and the 5.2 assumptions table (Tabel 17 precursor) have no caption (original style; left as is). The assumptions table above Tabel 17 could get its own caption if desired.
- Section 5.7 is now long (4 more tables); consider a page break before "Skenario yang dipakai".

## (d) Assumptions / need client confirmation
- Reading of "halaman 26" = 5.4 map table (not Tabel 17/18). If the client meant Tabel 18 or the 5.2 values table, the new column notes cover Tabel 18 but 5.2 untreated.
- "Ujung rentang yang dipakai" (which end for which purpose) is our proposal, not from D11/D13.
- "[perlu diverifikasi: penyebab rinci selisih per klaster ...]" placeholder in the "Mengapa berbeda" paragraph: D11/D13 do not explain the cluster-level divergence; our per-cluster comparison is our own arithmetic on D11 Tabel 8.2 and D13.
- Statement that S2 "doubles the pipeline" comes from D11 section 12.3; statement that S3 uses the pipeline is not made (D11 silent).
- Row "Kandungan domestik rendah/tinggi" assumes Tabel 21 uses the lower/upper bounds of Tabel 19 ranges (D11 Tabel 8.5 note: "rentang sesuai Tabel 8.1").
