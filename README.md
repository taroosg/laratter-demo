# Laratter

## About

Twitter ライクな SNS の Laratter です．Laravel を用いて実装されています．

## 機能と使い方

右上の「Register」からメールアドレスとパスワードでユーザが作成できます．

### tweet の作成

ログインすると「Create」画面から tweet が tweet が投稿できます．

### tweet の一覧表示

一覧画面（Index）に表示されます．

### tweet の編集と削除

自分の投稿した tweet は編集や削除ができます．

一覧画面に表示された自分の tweet 部分に表示されている編集ボタンや削除ボタンから処理を実行できます．

### favorite 機能

気に入った tweet には 💟 ボタンをクリックすることで favorite ができます．💟 ボタンの横には favorite されている数が表示されます．

### マイページ

マイページには自分の投稿した tweet が一覧で表示されます．

## その他

アーキテクチャはシンプルな MVC となっており，画面の構成には Laravel の blade テンプレートと，CSS に tailwind.css を用いています．

各処理の実装にはできる限り Laravel 組み込みのメソッドで実装しており，独自の実装は避けたものとなっています．

## License

Laratter is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
