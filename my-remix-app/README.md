## セットアップ
```
npx create-remix@latest
```

## プロジェクトstackタイプ
https://remix.run/docs/en/v1/pages/stacks
- The Blues Stack: Node.js PostgreSQL DB. プロダクションとかに使う
- The Indie Stack: Node.js SQLite. websites(blog, marketing, content site)にに適している。プロトタイプとかに向いてる。Bluesへの移行が後から簡単にできる。
- The Grunge Stack: DynamoDBのようなサーバレスに向いてる。AWS環境とかに適している。

## migrate
```
npx remix init
```