# Classification and Summarization of Windows 10 and Windows 11 Growth
Trends in Windows Operating System Usage Worldwide: Classification and Summarization of Windows 10 and Windows 11 Growth

# Project Overview
Analisis tren adopsi Windows 10 vs Windows 11 secara bulanan untuk melihat siapa yang naik/turun dan implikasinya bagi pengguna, organisasi, dan ekosistem perangkat.

## Raw Dataset Link
- CSV: [windows_version-ww-monthly-202407-202507.csv](data/windows_version-ww-monthly-202407-202507.csv)
- https://gs.statcounter.com/windows-version-market-share/desktop/worldwide?utm_source=chatgpt.com
  source dataset 

## Analysis Process
1. Load CSV dari GitHub Raw di Google Colab.
2. Parsing kolom tanggal (`YYYY-MM`) → dibuat kolom `month`.
3. Visualisasi tren **Windows 10 vs Windows 11** dalam grafik time series.
4. Hitung perubahan month-over-month (delta) dan rangkum temuan utama.
5. Simpan grafik hasil analisis ke folder `images/`.

## Insight & Findings
- **Windows 10**: menunjukkan tren stabil hingga bulan juni market share selama periode analisis namun mengalami penurunan
  di bulan juli dan seterusnya menandakan banyak pengguna bermigrasi ke versi lebih baru.
- **Windows 11**: memperlihatkan tren kenaikan stabil, konsisten dengan strategi distribusi Microsoft yang mendorong adopsi OS terbaru.
- Pergeseran pengguna terlihat jelas, dengan beberapa bulan tertentu terjadi lonjakan signifikan pada Windows 11.

## AI Support Explanation
- Menggunakan **IBM Granite** untuk:
  - Membantu menyusun pipeline analisis (data preparation, visualisasi, dan perhitungan perubahan).
  - Membuat ringkasan berbasis aturan (month-over-month delta, top increases).
  - Menyusun rekomendasi praktis serta draft naskah presentasi.
- Granite dipakai sebagai *AI assistant* untuk mempercepat proses dokumentasi, menjelaskan insight, dan memberikan kerangka laporan yang konsisten.


