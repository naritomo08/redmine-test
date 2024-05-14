# redmine-test

## 展開方法

```bash
git clone https://github.com/naritomo08/redmine-test.git
cd redmine-test
docker-compose build
docker-compose up -d

以下のサイトを参照する。
http://localhost:33000
```

## Dockerコンテナログイン

```bash
docker-compose exec redmine /bin/bash
docker-compose exec postgres /bin/bash
```
