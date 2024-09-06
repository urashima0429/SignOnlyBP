# Forward Forward Tests

## Dockerイメージのビルド
```bash
docker build -t sign-only-bp-env:latest .
```

## Dockerコンテナの起動
```bash
docker run -it --gpus all -p 8888:8888 -v ${PWD}/data:/app sign-only-bp-env:latest
```

## Jupyter Notebookの起動
[http://localhost:8888](http://localhost:8888)