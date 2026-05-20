# DCT Watermarking
- DCT dan IDCT manual without built-in DCT
- Watermark biner 32x32 with fixed seed
- Embedding di channel Y di ruang warna YCbCr
- Rotating multi-position mid-frequency coefficient
- Simulasi kompresi JPEG manual
- Evaluasi dengan PSNR dan BER
- Visualisasi original, watermarked, difference, dan hasil ekstraksi watermark

Program pakai pendekatan DCT-based watermarking. Gambar dibagi jadi blok 8x8, terus setiap blok diubah ke domain frekuensi pake DCT. 
Watermark disisipin pake metode QIM, ubah parity hasil kuantisasi koefisien DCT biar sesuai dengan bit watermark.
