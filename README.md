# Analisis Historis IHSG (1995–2025) — 30 Tahun Pergerakan Pasar Modal Indonesia

## 1. Deskripsi Proyek
Analisis berbasis Data Analytics untuk membongkar pola pertumbuhan, volatilitas, dan siklus krisis-pemulihan Indeks Harga Saham Gabungan (IHSG) selama 30 tahun terakhir. Tujuan utama analisis ini adalah memberikan pemahaman berbasis data mengenai karakteristik risiko jangka panjang pasar modal Indonesia bagi investor, analis, maupun pemangku kepentingan lain.

## 2. Latar Belakang
IHSG adalah barometer utama pasar modal Indonesia, mencerminkan performa gabungan seluruh saham yang tercatat di Bursa Efek Indonesia (BEI). Selama 30 tahun terakhir, IHSG telah melalui berbagai siklus ekonomi besar — Krisis Moneter 1998, Krisis Finansial Global 2008, hingga Pandemi Covid-19 2020. Memahami pola historis pertumbuhan, volatilitas, dan pemulihan pasca-krisis penting untuk merumuskan strategi investasi dan manajemen risiko yang lebih matang.

## 3. Problem Statement
"Bagaimana pola pertumbuhan, volatilitas, dan siklus krisis-pemulihan IHSG selama periode 1995–2025 dapat memberikan gambaran mengenai karakteristik risiko dan perilaku pasar modal Indonesia dalam jangka panjang?"

## 4. Dataset
IHSG Daily Historical Price — 7.681 baris, 6 kolom (Date, Open, High, Low, Close, Volume). Mencakup periode 2 Januari 1995 hingga 2025, bersumber dari data historis Jakarta Composite Index (Kaggle).

## 5. Proses
- Business Understanding
- Data Understanding
- Exploratory Data Analysis (EDA)
- Feature Engineering (Daily Return, Cumulative Return, Drawdown, Rolling Volatility)
- Uji Hipotesis (Kruskal-Wallis, Spearman Correlation)
- Insight & Business Recommendation

## 6. Library
pandas, numpy, matplotlib, seaborn, scipy.stats

## 7. Struktur Folder
```
ihsg_project/
├── data/                  # dataset mentah & hasil export untuk dashboard
├── notebooks/             # jupyter notebook analisis
├── dashboard/             # export data untuk Tableau
├── docs/                  # dokumentasi tambahan
├── requirements.txt
└── README.md
```

## 8. Cara Menjalankan
```bash
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/01_business_understanding_and_eda.ipynb
```
