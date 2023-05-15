# 記事004 Github

[記事]()のコード管理

## 環境構築

Docker + Compose 
```shell
git clone https://github.com/
docker compose up -d
```
Anaconda
```shell
conda install gdal

# ミラー補完
conda install -c conda-forge gdal
conda install gdal==3.0.2
conda install gdal==3.4.3
pip install -r env/requirements.txt

jupyter-lab --NotebookApp.token='' --allow-root --no-browser --port 8888 --ip=0.0.0.0
```