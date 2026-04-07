# Claude Code Tutorial

## チュートリアル

- [日本語](https://colab.research.google.com/github/engineercafejp/claude-code-tutorial/blob/main/ja.ipynb)
- [英語](https://colab.research.google.com/github/engineercafejp/claude-code-tutorial/blob/main/en.ipynb)

## プロジェクト概要

Google Colabでスライドショーとして表示するためのJupyter Notebookで構成される初心者向けチュートリアル。以下は、チュートリアルの構成。

1. Claude Codeとは？
2. Claude Codeのインストール（Windows・macOS）
    - GUI版
    - CLI版
    - VSCode・Antigravity拡張機能
3. Hello World
    - 作業ディレクトリの作成
    - Hello Worldを表示するスクリプトの作成（macOS: bash / Windows: PowerShell）
    - Ascii ArtのHello Worldを表示するスクリプトへの改修
4. 初心者が抑えるべきコマンド
    - Shift+Tab：Permissionモードの切り替え（Normal → Auto-Accept → Plan Mode）
    - /model：使用モデルの変更
    - /status：ステータスの確認
    - /resume：過去のセッションの再開
    - /clear：会話履歴のリセット
    - /init：CLAUDE.mdを自動生成
    - ?：キーボードショートカット一覧の表示
    - Esc：実行中のアクションを停止
    - Ctrl+C：Claude Codeを終了
5. 初心者が抑えるべきノウハウ
    - Plan Modeの使い方（Shift+Tabで切り替え）
        - 読み取り専用モードでコードを分析・計画立案
        - 実装前に「探索 → 計画 → 実装」の流れを徹底する
    - 具体的なプロンプトを書く
        - 「バグを直して」ではなく「〇〇画面で◻◻操作した時に起きるバグを直して」
    - コンテキスト管理
        - 関連のないタスク間では /clear でリセット
6. 福岡市の天気予報（https://www.jma.go.jp/bosai/forecast）の取得

## エージェントへのお願い

- 日本語チュートリアルは `ja.ipynb` に記載
- 最新の情報をインターネットで調べてチュートリアルを作成
- 絵文字を多めにして、専門用語を少なく適度に簡潔にまとめる
