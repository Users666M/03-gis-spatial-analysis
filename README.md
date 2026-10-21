# Career and Competition in Industrial Era with GIS
Studi kasus sesi **Career and Competition in Industrial Era with GIS** - *Informatics Practitioner Lecture Series, Informatika Unib*.

**Tema:** deteksi dan atribusi penyebab deforestasi di Provinsi Bengkulu. Data **sintetis** (untuk pembelajaran).

**Tujuan:** Menerapkan analisis GIS: pemetaan, hotspot berbasis grid, ringkasan per wilayah, dan ekspor GeoJSON.

## Hasil singkat
- Grid hotspot 0,1 derajat, ringkasan per kabupaten, peta sebaran dan kepadatan
- `data/alerts.geojson` otomatis tampil sebagai peta di GitHub
- Alert terluas: Bengkulu Utara (sekitar 3.700 ha)

## Struktur
```
src/generate_data.py   # data sintetis
src/gis_analysis.py    # hotspot, ringkasan wilayah, GeoJSON
data/alerts.geojson    # bisa dilihat langsung di GitHub (peta)
reports/
```

## Menjalankan
```bash
pip install -r requirements.txt
python -m src.generate_data
python -m src.gis_analysis
```
## Repo lain dalam rangkaian studi kasus ini
- `01-data-analysis-and-ai`
- `02-hpc-parallel-processing`
- `04-machine-learning-intro`
- `05-hci-data-visualization`
- `06-deforestation-drivers-satellite-ai`
