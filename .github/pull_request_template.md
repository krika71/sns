## 実装した機能

例）いいね機能実装

## やったこと

下記は例
- エンドポイントの作成
  - /like
  - Post形式
  - リクエスト
    - userId:int
    - postId:int
  - レスポンス
    - 成功
      - success:"いいねに成功しました"
    - エラー
      - ステータスコードを元にデフォルトのエラーを返す
- service層に関数を切り分けた

## 補足
- 補足事項があれば
- [ ] やることリストでもok