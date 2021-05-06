# Docker最初のサンプル

実行コマンド

```bash
docker build -t mypython:0.1 .
docker run -t --rm -v ${PWD}:/mnt mypython:0.1 python hello.py
```
