# Simulasi Dinamika Homeostasis pH Darah: Prediksi Asidosis dan Optimasi Intervensi Medis

Repositori ini berisi implementasi simulasi komputasional untuk memodelkan kinetika reaksi kimia _buffer_ darah dalam merespons akumulasi asam laktat. Proyek ini dikembangkan sebagai bagian dari tugas besar mata kuliah IF3211 Komputasi Domain Spesifik.

## Deskripsi Proyek
Model ini menggunakan sistem **Ordinary Differential Equations (ODE)** untuk memetakan perubahan molaritas molekul $H^+$, $HCO_3^-$, dan $H_2CO_3$ secara kontinu. Simulasi ini bertujuan untuk:
1. **Pemetaan sistem fisiologis**: mensimulasikan dan memvisualisasikan dinamikan penurunan tingkat pH darah secara _real-time_ di bawah pengaruh laju infusi asam laktat secara konstan.
2. **Analisi _tipping point_**: Mengevaluasi kurva trajektori pH dalam kegagalan sistem terhadap  degradasi kapasitas *buffer*
3. **Optimasi intervensi injeksi**: Mengimplementasikan penggunaan algoritma pencarian akar (_root finding_) menggunakan metode Brent (_Brent's Method_) untuk menentukan takaran dosis injeksi $NaHCO_3$ ke dalam sistem secara otomatis dengan presisi tinggi. Optimasi ini memastikan pemulihan sistem dengan baik di bawah ancaman komplikasi medis berdasarkan batas toleransi tubuh manusia.

## Struktur Repositori
- `simulasi.ipynb`: Jupyter Notebook utama yang berisi seluruh kode simulasi dan visualisasi hasil eksperimen.
- `assets/`: Folder berisi grafik hasil simulasi dalam format `.png`.

## Persyaratan (Dependencies)
Proyek ini dijalankan dengan Python 3.x dan membutuhkan pustaka berikut:
```bash
pip install numpy scipy matplotlib
```

## Kontributor
| Nama                           | NIM      |
|--------------------------------|----------|
| Bertha Soliany Frandi          | 13523026 |
| Rafen Max Alessandro           | 13523031 |
| ALoisius Adrian Stevan Gunawan | 13523054 |