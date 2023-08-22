# wordpress_on_docker
## 要件
- docker-composeを使用してwordpressの開発環境を構築する
- wordpress:php7.4-apache, mysql:8
- dev-wordpress.menta.meでwordpressが動かすことを確認する
  - ローカルのhostsファイルに127.0.0.1 dev-wordpress.menta.meを追加

## テスト証跡
### docker-compose upの実行結果
```
fukuiryousukenoMacBook-Pro:dev fukuiryousuke$ docker-compose up -d --build
Creating network "dev_default" with the default driver
Creating dev_db_1 ... done
Creating dev_wordpress_1 ... done
```

### dev-wordpress.menta.meでの接続確認
![image](https://user-images.githubusercontent.com/60649665/164216512-14115d0b-6283-45bb-88d3-dfd617383b7a.png)
![image](https://user-images.githubusercontent.com/60649665/164216738-b0d6fdc1-d521-4a61-b01a-473dd4c982db.png)
