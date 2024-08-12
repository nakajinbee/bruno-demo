# bruno-demo

APIクライアントツールの調査用のリポジトリ

・JSONPlaceholder（無料のフェイクAPI）
https://jsonplaceholder.typicode.com/

・Dog API (犬の画像を返すAPI)
https://dog.ceo/dog-api/


Postmanと何が違うのか（2024/7/26時点）
(https://www.usebruno.com/compare/bruno-vs-postman)


Postman
- JSONでリクエストデータを管理
- クラウドに保存
- 独自のプロキシサーバーを使用してAPIリクエストを行う
- 優良($15ドル)のチームコラボレーション機能

Bruno
- Bru言語を使ってデータを管理
- システム上のフォルダに直接保存
- 自身のコンピューターから直接APIリクエストを行う
- Gitで管理することにより、チームで共有できる。

BRUNOを使ってみて



※注意点
BRUNOのバージョンに注意
古いバージョンだとパスパラメータの指定等に対応しておらず、読み込めないことがある。
