# Ev-Performance-Analysis
Analisis performa kendaraan listrik (EV) dengan fokus pada kecepatan puncak, kapasitas baterai, jangkauan, akselerasi, torsi maksimum, serta distribusi drivetrain.
Project ini mencakup validasi data dan visualisasi menggunakan dashboard interaktif di Power BI.

## 📂 Struktur Repo
- **data/** → data raw/cleaned  
- **notebooks/** → notebook eksplorasi  
- **dashboard/** → Power BI/pdf preview

## 🔍 Data Validation
Dataset sudah dicek:  
- ✅ Terdapat sedikit nilai null, sudah ditangani
- ✅ Tidak ada duplikasi pada data model/brand
- ✅ Tipe data sudah sesuai (numerik & kategorikal)

## 📊 Insight Utama
- Top Speed: Maserati memimpin dengan rata-rata kecepatan puncak tertinggi mendekati 280 km/h.
- Baterai & Jangkauan: Terdapat korelasi positif, kapasitas baterai lebih besar → jangkauan lebih jauh.
- Akselerasi: EV tercepat menorehkan akselerasi 0–100 km/h hanya dalam 2.20 detik.
- Torsi: Model dengan torsi maksimum mencapai 1350 Nm.
- Drivetrain: Distribusi drivetrain didominasi oleh AWD (39.96%), disusul FWD (32.64%) dan RWD (27.41%).
  
## 📌 Tools
- Python (Pandas)  
- Power BI  
