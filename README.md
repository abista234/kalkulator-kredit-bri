# Kalkulator Kredit BRI — Unit Sengon

Hitung sendiri angsuran **KUR** (bunga 6% per tahun) — cepat, mudah, bisa dibuka dari HP.

## Fitur
- Perkiraan angsuran per bulan, total bunga, total yang dikembalikan
- **Plafon yang PAS buatmu**: isi rata-rata pendapatan per bulan → pinjaman maksimal
  dari 75% pendapatan (KUR annuitas 6% & Bank BKK flat 9%)
- Rincian angsuran bulanan (angsuran, pokok, bunga, sisa hutang)
- **Perbandingan dengan Bank BKK (bunga flat 9%)** — cicilan & selisih per bulan
- **Bagikan ke WhatsApp**: teks ringkasan + gambar rincian siap kirim
- Ekspor ke gambar (PNG) & cetak/PDF

## Rumus
- KUR (annuitas): `A = P x i / (1 - (1+i)^-n)`, `i = bunga tahunan / 12`
- BKK (flat): `bunga = P x rate x bulan / 12`, `cicilan = (P + bunga) / bulan`
- Plafon pas: `angsuran = 75% x pendapatan`

Angka bersifat indikatif — mengikuti perhitungan resmi bank.
