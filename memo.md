# memo

## ■ solidus

### ◆ solidusが動かせるようになるまで

1. ImageMagick をインストールする(公式から落として普通にインストールする)  
   rails s するコンソールで、magick を実行し、パスが通っていることを確認する
2. gem install deface を Gemfileに追加する
3. bundle install
4. bundle exec rails g spree:install
  
※ bundle exec rails db:migrate は実行しなくてもDB勝手にできてた  
  
完了したら、http://localhost:3000 にアクセス。  
※初回アクセスに凄い時間かかる＆画像が上手く表示されないけどとりあえず良いや。。  
  
[Spreeの後継ECシステム、Solidusのインストールメモ](https://qiita.com/yuskamiya/items/4edf7dc763c079f393ee)

---

### ◆ デフォルトのID/PASSWORD

Email [admin@example.com]:
Password [test123]:

---

### ◆ URL

管理用：http://localhost:3000/admin  
一覧：http://localhost:3000/rails/info/routes  

### ◆ 日本語訳

[[日本語訳] PREFERENCES - DEVELOPER GUIDE | SPREE COMMERCE](https://qiita.com/yuskamiya/items/2c8e00ff384e89a86254)
