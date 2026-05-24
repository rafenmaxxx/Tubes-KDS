# Simulasi Dinamika Homeostasis pH Darah: Prediksi Asidosis dan Optimasi Intervensi Medis

Repositori ini berisi implementasi simulasi komputasional untuk memodelkan kinetika reaksi kimia _buffer_ darah dalam merespons akumulasi asam laktat. Proyek ini dikembangkan sebagai bagian dari tugas besar mata kuliah IF3211 Komputasi Domain Spesifik.

## Deskripsi Proyek
Model ini menggunakan sistem **Ordinary Differential Equations (ODE)** untuk memetakan perubahan molaritas molekul $H^+$, $HCO_3^-$, dan $H_2CO_3$ secara kontinu. Simulasi ini bertujuan untuk:
1. **Memetakan trajektori** penurunan pH darah di bawah infusi asam laktat konstan.
2. **Menganalisis korelasi** antara degradasi kapasitas *buffer* dengan titik kritis (*tipping point*) kegagalan sistem.
3. **Melakukan optimasi** terhadap kombinasi intervensi terapeutik berupa injeksi $NaHCO_3$ untuk menemukan jendela waktu dan dosis injeksi yang paling efektif dalam memperpanjang waktu ketahanan fisiologis.

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