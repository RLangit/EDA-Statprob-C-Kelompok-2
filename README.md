# Fisik vs. Digital: Analisis Perbandingan Kerentanan Media Penyimpanan Data Kesehatan US

## Anggota Kelompok (Kelompok 2)

| Nama | NRP |
|---|---|
| Adhitya Bayu Pratama | 5027261045 |
| Via Nur Belaya | 5027261060 |
| Raditya Langit Nugraha | 5027261072 |

## Topik

**Cyber Security — Data Breaches**

Analisis terhadap insiden kebocoran data kesehatan di Amerika Serikat, dengan fokus membandingkan kerentanan media penyimpanan **fisik (dokumen kertas)** dan **digital (perangkat/sistem elektronik)**.

## Sumber Dataset

- **Dataset:** [Major US Health Data Breaches — Kaggle](https://www.kaggle.com/datasets/thedevastator/major-us-health-data-breaches)
- **Sumber asli:** data.world (sudah tidak aktif) & [HHS OCR Breach Portal](https://ocrportal.hhs.gov/ocr/breach/breach_report_hip.jsf)
- **Dikumpulkan oleh:** *Office for Civil Rights* (OCR), di bawah *U.S. Department of Health and Human Services* (HHS), berdasarkan mandat wajib lapor HIPAA/HITECH Act sejak tahun 2009.

## Lisensi

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — bebas dibagikan dan diadaptasi untuk tujuan apa pun (termasuk komersial), selama mencantumkan atribusi ke sumber asli dan menyertakan tautan lisensi.

## 3 Temuan Utama

## Cara Menjalankan Notebook

1. **Undul file yang dibutuhkan** Unduh file yang berada di github ini, pastikan file `eda_kelompok_02.ipynb` dan `breach_report.csv` terinstall dan berada pada satu folder yang sama
2. **Unduh dan Install Miniconda** Pastikan perangkat yang akan gunakan untuk melihat notebook ini sudah terinstall Anaconda/Miniconda agar dapat menjalankan notebooknya.
3. **Buat environment untuk membuka notebooknya** Buat environment python 3.11 untuk membuka dan menjalankan notebook
```bash
conda create -n namaEnvironment python=3.11 -y
conda activate namaEnvironment
```
4. **Install paket yang dibutuhkan** install paket ini agar kode berjalan sesuai yang di inginkan pembuat
```bash
conda install -c conda-forge jupyter pandas matplotlib seaborn -y
```
5. **Jalankan Jupyter Notebook** Masukan folder proyek kalian (yang berisi `eda_kelompok_02.ipynb` dan `Breach_report.csv`), lalu jalankan jupyter dengan command berikut:
```bash
cd lokasi/folder/proyek1
jupyter notebook
```
>browser akan otomatis terbuka dan kalian bisa mengakses file yang sudah di download

6. **Run semua cell secara berurutan** Agar mendapat hasil akhir yang sesuai pembuat, jalankan cell secara berurutan dari atas hingga bawah, maka dipastikan hasil akhir akan sesuai.
