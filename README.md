# new_zerochan_docker

## 概要

New_0ch_Plus のデフォルトの状態のDocker関連のファイル置き場
<https://github.com/PrefKarafuto/New_0ch_Plus/>

```bash
docker compose -p プロジェクト名 up
```

で起動
<http://localhost:8080/test/admin.cgi>にアクセスすれば見れます


```bash
docker compose -p プロジェクト名 down
```
で終了

中で作成したファイル等はrootになるので注意してください
devcontainer.json等は現在作成中です


## ディレクトリ構成

```plain
.
├── Dockerfile
│   ├── Readme.txt
│   └── test
└── docker-compose.yml
```
