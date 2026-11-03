# 💸 Buy/Bye LQ45 Dashboard (Streamlit Edition)

Bespoke Decision Support System (DSS) dashboard for Indonesia's LQ45 blue-chip stock index combining Fundamental, Technical, and Retail Sentiment analysis with an interactive Capital Allocation Engine powered by Markowitz Modern Portfolio Theory (MPT).

## 🚀 Fitur Utama
- **📂 Market Overview:** Ringkasan performa bursa harian, pergerakan indeks IHSG & LQ45, dan status sentimen agregat pasar.
- **📈 Multi-Pillar Analysis:** Candlestick chart interaktif dilengkapi indikator teknikal (EMA 20 & SMA 50) serta parameter valuasi fundamental (P/E, PBV, Div Yield, Beta).
- **💬 Retail Sentiment Stream:** Analisis sentimen dinamis dari aliran komentar forum bursa secara real-time dengan pengelompokan label sinyal transaksi (BUY, STRONG BUY, SELL, STRONG SELL, HOLD).
- **🔍 Screener Saham:** Saring semesta saham LQ45 secara presisi berdasarkan batas kustom rasio valuasi finansial.
- **💼 Portfolio Planner:** Optimasi alokasi modal investasi dengan algoritma simulasi Monte Carlo Markowitz Efficient Frontier lengkap dengan lot calculator otomatis.

---

## 🛠️ Cara Menjalankan Aplikasi Secara Lokal

### Prasyarat
Pastikan Anda sudah menginstal **Python 3.8 - 3.11** di perangkat Anda.

### 1. Kloning Repositori & Masuk ke Direktori
```bash
git clone <url-repositori-anda>
cd <nama-folder-repositori>
```

### 2. Instal Dependensi
Gunakan berkas `requirements.txt` yang telah disediakan untuk menginstal seluruh pustaka pendukung:
```bash
pip install -r requirements.txt
```

### 3. Jalankan Aplikasi Streamlit
```bash
streamlit run streamlit_app.py
```

---

## 🌐 Deploy di Streamlit Community Cloud (Gratis & Cepat)

1. Unggah kode proyek ini ke repositori **GitHub** pribadi Anda.
2. Akses [Streamlit Community Cloud](https://share.streamlit.io/) lalu masuk menggunakan akun GitHub Anda.
3. Klik tombol **New app**, lalu pilih repositori, branch `main`, dan isi Main file path dengan `streamlit_app.py`.
4. Klik **Deploy!** Aplikasi Anda akan langsung siaran langsung (Live) dalam hitungan menit tanpa ribet.
