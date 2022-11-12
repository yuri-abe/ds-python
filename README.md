# ds-python

## 環境構築

### 初期セットアップ

```
# DockerHubにログイン
docker login

# 使用するdockerimageをpull
docker pull datascientistus/ds-python-env

# docker run
docker run -v /$HOME/ds-python/work:/work -p 8888:8888 --name my-env datascientistus/ds-python-env
```

- ブラウザで`localhost:8888`にアクセス

### docker container の削除

```
# 停止しているコンテナ含む一覧表示
docker ps -a

# containerの削除
docker rm <container ID>
```
