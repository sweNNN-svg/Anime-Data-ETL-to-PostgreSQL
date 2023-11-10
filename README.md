# Anime Veri Seti ve PostgreSQL ETL Pipeline

Bu proje, anime veri seti üzerinde veri manipülasyonu yaparak elde edilen verileri PostgreSQL veritabanına aktaran bir ETL pipeline'ını içermektedir.

## Proje Dosyaları

- `anime.csv`: Orijinal anime veri seti
- `anime_data.csv`: Veri manipülasyonu yapılmış anime veri seti
- `anime_data_fixed.csv`: İhtiyaç duyulan sütunlara sahip son hali
- `Postgres-Python.ipynb`: PostgreSQL ve Python kullanarak yapılmış bir Jupyter Notebook
- `veri-manipulasyonu.ipynb`: Veri manipülasyonu işlemlerini içeren Jupyter Notebook

## Kullanım

1. **Veri Manipülasyonu:**
   - `veri-manipulasyonu.ipynb` dosyasını açarak veri manipülasyonu işlemlerini inceleyebilirsiniz.

2. **PostgreSQL Bağlantısı:**
   - `Postgres-Python.ipynb` dosyasını kullanarak PostgreSQL veritabanına bağlantı sağlayabilir ve verileri aktarabilirsiniz.

## Kurulum

1. Python ve Jupyter Notebook yüklü değilse, [Python'un resmi web sitesinden](https://www.python.org/) indirip kurun.
2. Gerekli Python paketlerini yüklemek için terminal veya komut istemcisine şu komutu yazın:
   pip install pandas psycopg2 sqlalchemy
