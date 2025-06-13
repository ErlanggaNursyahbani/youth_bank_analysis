# 🧠 Youth Bank Campaign Analysis

Notebook ini berisi analisis dan visualisasi terhadap data kampanye perbankan yang ditargetkan pada klien muda. Analisis mencakup eksplorasi data demografis, perilaku klien, dan efektivitas kampanye marketing.

## 📊 Deskripsi Dataset

Terdapat dua dataset utama:

- `clients.csv`: berisi informasi demografis dan karakteristik klien bank.
- `campaigns.csv`: berisi hasil dan detail kampanye marketing yang dilakukan oleh bank.

## 🔍 Fokus Analisis

- Karakteristik klien yang merespon positif terhadap kampanye.
- Perbandingan distribusi usia, pendidikan, dan pekerjaan terhadap hasil kampanye.
- Evaluasi durasi dan frekuensi kontak selama kampanye.
- Korelasi antara variabel seperti pekerjaan, default, dan durasi terhadap keberhasilan kampanye.

## 📌 Insight Utama

Beberapa temuan penting dari analisis:
- Klien dengan pekerjaan di sektor siswa dan usia tua pensiunan cenderung lebih merespons positif.
- Durasi panggilan memiliki korelasi kuat terhadap keberhasilan kampanye.
- Nasabah yang tidak memiliki pinjaman atau berstatus siswa cenderung lebih menerima tawaran.

## 🖼️ Visualisasi

Semua grafik yang dihasilkan dari notebook disimpan di folder `visual/`, termasuk:
- Distribusi usia klien
- Respon kampanye berdasarkan pekerjaan
- Korelasi antar variabel
- Heatmap dan bar chart 

## 🚀 Cara Menjalankan

1. Pastikan file berikut tersedia di struktur direktori:
   - `datasets/clients.csv`
   - `datasets/campaigns.csv`
   - `youth_campaign_analysis.ipynb`

2. Buka notebook:
   ```bash
   jupyter notebook youth_campaign_analysis.ipynb
