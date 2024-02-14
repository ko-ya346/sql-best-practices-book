# BigQuery
- クエリのパフォーマンスに関する内容
https://cloud.google.com/bigquery/docs/best-practices-performance-compute?hl=ja

# Metabase
- 書きたいもののイメージに相当近い
- 正確性 -> 可読性 -> 最適化
- まずはデータについて知る
- 早い段階でデータを削除できるほどよい
- ガイドライン
-- コメント 
-- 複数テーブルのエイリアス
-- groupby はカーディナリティの降順で
-- in より exists
-- CTE を使う
https://www.metabase.com/learn/sql-questions/sql-best-practices

# sqlstyle
- 命名規則とか
- 2005 年出版の書籍がもとっぽい
https://www.sqlstyle.guide/

# sql-best-practices (AnalyticsMentor.io の創設者)
- 悪い例がたくさんあって分かりやすい
- 規約の話っぽい
- サブクエリはQAしづらいから推奨してなかった（自明の処理であればOKなのかも）
- 適切なコメント (a > 100 は処理は分かるけどそれを行う理由が分からない)
https://medium.com/@BrandonSouthern/sql-best-practices-e1c61e96ee27

# stratascratch best practices
- 一貫したエイリアス
https://www.stratascratch.com/blog/best-practices-to-write-sql-queries-how-to-structure-your-code/

# gitlab
- かなり丁寧でよい
- id, name, type は曖昧なので識別する内容を接頭辞として付ける
- boolean は has_, is_, does_ で始まる
- timestamp は _at で終わる、常に UTC
- date は _date で終わる
https://handbook.gitlab.com/handbook/business-technology/data-team/platform/sql-style-guide/

# brooklyn-data
- gitlab のSQLスタイルのページにリンク貼ってた
- こういう形で社内に展開するところから始めてもよさそう
- かなり実践的でよい
https://github.com/brooklyn-data/co/blob/main/sql_style_guide.md

# mattm
https://github.com/mattm/sql-style-guide


# kickstarter
https://gist.github.com/fredbenenson/7bb92718e19138c20591