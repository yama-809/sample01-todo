# 📝 TODO アプリ

個人用のシンプルなTODOウェブアプリです。インストール不要、ブラウザだけで動作します。

## デモ

**Vercel**: https://sample01-todo.vercel.app
**GitHub Pages**: https://yama-809.github.io/sample01-todo/

## 機能

- タスクの追加・完了チェック・削除
- タグ分け（💼 仕事 / 🏠 プライベート）
- 期日設定とカラーバッジ表示（期限切れ / 今日 / 今後）
- タグ・期日によるフィルター
- データはブラウザのlocalStorageに自動保存
- スマホ対応レイアウト

## 使い方

1. タスク名を入力
2. タグ（仕事／プライベート）と期日を選択
3. 「追加」ボタンまたはEnterキーで追加

## ローカルで起動する

```bash
cd todo
npx http-server
```

ブラウザで http://localhost:8080 を開く。

または `index.html` をブラウザで直接開いても動作します。

## 技術スタック

- HTML / CSS / JavaScript（フレームワークなし）
- データ永続化: localStorage
- 外部依存: なし

## ファイル構成

```
todo/
├── index.html   # アプリ本体
└── docs/
    └── spec.md  # 仕様書
```
