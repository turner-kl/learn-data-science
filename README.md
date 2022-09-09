
M1 Macなら`--platform linux/amd64`

- イメージをビルド
```
docker build . -t ds-lab
```

- コンテナ起動
```
docker run -p 8888:8888 -v $(pwd)/work:/work --name ds-lab ds-lab
```