# hugo

* イメージをビルド  
```
docker-compose build --no-cache
```
* コンテナ起動
```
docker-compose up -d
```
*  コンテナ内へ
```
docker exec -it hugo_hugo_1 /bin/bash
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
*  コンパイルしサーバーを起動
```
hugo server
```
