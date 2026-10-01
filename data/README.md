# Data Tugas 1

## Dataset yang Dipilih

Isi informasi berikut sebelum Milestone 1.

| Item | Isi |
|---|---|
| Nama dataset | `Deteksi titik panas (active fire / hotspot) VIIRS S-NPP 375 m, data standar, Indonesia` |
| Sumber | `NASA FIRMS, halaman "Download yearly summary by country": (https://firms.modaps.eosdis.nasa.gov/country/)` |
| Lisensi/ketentuan pakai | `Data terbuka NASA; sitasi dan kebijakan: https://www.earthdata.nasa.gov/engage/open-data-services-software-policies/data-use-policy` |
| Ukuran | `76.3 MB total CSV Indonesia (memenuhi syarat: > 1.000.000 baris / >= 500 MB)` |
| Periode data | `Data yang diambil dari rentang tahun 2019 - 2024` |
| Unit analisis | `Satu deteksi titik panas (satu piksel 375 m pada satu waktu lintasan satelit` |

## Tempat Mencari Dataset

Pilih dataset Indonesia yang legal digunakan, dapat didokumentasikan sumbernya, dan memenuhi batas ukuran tugas.

| Situs | Kegunaan |
|---|---|
| [Satu Data Indonesia](https://data.go.id/) | Portal data terbuka lintas instansi pemerintah Indonesia. |
| [Badan Pusat Statistik](https://www.bps.go.id/) | Statistik sosial, ekonomi, kependudukan, dan data wilayah. |
| [BMKG Data Online](https://dataonline.bmkg.go.id/) | Data cuaca, iklim, gempa bumi, dan observasi meteorologi. |
| [Hugging Face Datasets](https://huggingface.co/datasets) | Dataset publik yang dapat dicari berdasarkan topik, bahasa, atau ukuran. |
| [Kaggle Datasets](https://www.kaggle.com/datasets) | Katalog dataset publik; periksa lisensi dan dokumentasi pembuatnya. |
| [Google Dataset Search](https://datasetsearch.research.google.com/) | Mesin pencari untuk menemukan dataset dari berbagai portal. |

## Cara Memperoleh Data

1. Buka URL sumber di atas.
2. Unduh file ke folder `data/raw/` tanpa mengubah data mentah.
3. Catat nama file dan checksum bila tersedia.
4. Ubah variabel `DATA_PATH` pada `notebooks/01_data_profiling.ipynb` agar menunjuk ke file tersebut.

## Aturan Penyimpanan

- Jangan commit dataset mentah atau hasil olahan berukuran besar ke Git.
- File pada `data/raw/` adalah data asli dan tidak boleh diubah.
- Simpan hasil transformasi yang dapat direproduksi pada `data/processed/`.
