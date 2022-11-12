# ds-python

## 環境構築

- terminal で実行

```
# DockerHubにログイン
docker login

# 使用するdockerimageをpull
docker pull datascientistus/ds-python-env

# docker run
docker run -v /$HOME/ds-python/work:/work -p 8888:8888 --name my-env datascientistus/ds-python-env
```

- ブラウザで`localhost:8888`にアクセス
