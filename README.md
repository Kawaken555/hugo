# hugo

* コンテナ起動
```
docker-compose up -d
```
* プロジェクトを作成
```
hugo new site test-blog
```
* テーマをダウンロード
```
cd themes
git clone https://github.com/budparr/gohugo-theme-ananke.git
```
*  コンテナ内へ
```
docker exec -it hugo_hugo_1 /bin/bash
```
*  コンパイルしサーバーを起動
```
hugo server
```
