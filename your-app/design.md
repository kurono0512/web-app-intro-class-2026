# わたしのアプリ設計

## 1. 題材
- 勉強した内容と学習状況を記録・管理するアプリ

## 2. テーブル設計
- テーブル名： studies
- カラム： id / title(勉強内容) / done(学習済み)

## 3. 変換後
- todos -> studies
- done -> done(意味は学習済み)
- todo.db -> studies.db
- /todos -> /studies