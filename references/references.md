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