# ansibleDevelopmentEnvironment

## ホスト側

### 環境起動方法
```
(ホスト側のVagrantfileがあるディレクトリにて実行)
vagrant up
vagrant provision
```

### アクセスURL
http://localhost:8100/ or
http://http://192.168.33.51/


### 共有ディレクトリ
ホスト側のwwwとゲスト側の/var/www/htmlは共有ディレクトリとなっている。

## ゲスト側

### インストールソフトウェア
* PHP5.5.9
* nginx 1.4.6

### ドキュメントルート
/var/www/html

### Nginx
設定ファイル  
/etc/nginx/conf.d/nginx.conf

ログファイル  
/var/log/nginx/[access|error].log
