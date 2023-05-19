# 記事004 Github

![img](title.png)

[記事](https://sorabatake.jp/32245)のコード管理

## コマンドと使用例一覧
[NoteBook](./src/sample.ipynb)

## 環境構築

Build 済みの取得
https://hub.docker.com/repository/docker/syu3090/gdal-analysis/general
```bash
docker pull syu3090/gdal-analysis:v0.1.0
docker run -p 8888:8888 -v src:/workspace syu3090/gdal-analysis:v0.1.0
````
JupyterLab Link:[http://localhost:8888](http://localhost:8888)

Docker + Compose 
```shell
git clone https://github.com/
docker compose up -d
```
Anaconda
```shell
conda install gdal
pip install -r env/requirements.txt
jupyter-lab --NotebookApp.token='' --allow-root --no-browser --port 8888 --ip=0.0.0.0
```

ミラー保管
```shell
conda install -c conda-forge gdal
conda install gdal==3.0.2
conda install gdal==3.4.3
```
