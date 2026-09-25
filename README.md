# Kalkulator Kredit BRI — Unit Sengon

Simulasi angsuran kredit dengan **cicilan tetap tiap bulan**:

- **KUR** — bunga 6% per tahun
- **Umum** — bunga 22% per tahun

## Fitur
- Cicilan per bulan, total bunga, total yang dikembalikan
- Rincian angsuran bulanan (angsuran, pokok, bunga, sisa hutang)
- **Simulasi balik**: isi kemampuan bayar nasabah → plafon maksimal (KUR & Umum)
- **Bagikan ke WhatsApp**: teks ringkasan + gambar rincian siap kirim
- Ekspor ke gambar (PNG) & cetak/PDF
- Mobile-friendly, tanpa backend

## Rumus
`A = P x i / (1 - (1+i)^-n)` dengan `i = bunga tahunan / 12`.

Plafon maksimal: `P = A x (1 - (1+i)^-n) / i`, dibulatkan ke bawah Rp100.000.

Angka bersifat indikatif — mengikuti SIK & sistem bank.
