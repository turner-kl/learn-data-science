
M1 Macなら`--platform linux/amd64`
```
docker build .
```

```
docker run -p 8888:8888 -v $(pwd)/work:/work --name ds-lab 8a2f2
```