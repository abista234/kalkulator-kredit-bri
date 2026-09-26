# Kalkulator Kredit BRI — Unit Sengon

Hitung sendiri angsuran **KUR** (bunga 6% per tahun) — cepat, mudah, bisa dibuka dari HP.

## Fitur
- Perkiraan angsuran per bulan, total bunga, total yang dikembalikan
- **Biaya & dana awal**: admin (Rp50rb < Rp50 jt, Rp100rb >= Rp50 jt), asuransi
  Kesehatan & Usaha Rp400rb, blokir saldo 2x angsuran → total disiapkan & dana yang dapat digunakan
- Rincian angsuran bulanan (angsuran, pokok, bunga, sisa hutang)
- **Simulasi balik**: isi cicilan yang sanggup dibayar → pinjaman maksimal
- **Perbandingan dengan Bank BKK (bunga flat 9%)**
- **Bagikan ke WhatsApp** (teks + gambar), ekspor PNG, cetak/PDF

## Rumus
- KUR (annuitas): `A = P x i / (1 - (1+i)^-n)`, `i = bunga tahunan / 12`
- BKK (flat): `bunga = P x rate x bulan / 12`, `cicilan = (P + bunga) / bulan`

Angka bersifat indikatif — mengikuti perhitungan resmi bank.
