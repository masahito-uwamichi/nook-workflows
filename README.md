[![Run nook action](https://github.com/masahito-uwamichi/nook-workflows/actions/workflows/run-nook.yml/badge.svg)](https://github.com/masahito-uwamichi/nook-workflows/actions/workflows/run-nook.yml)

# nook-workflows
[umiyuki/nook](https://github.com/umiyuki/nook)を定期的に実行するワークフローを試しに作ってみるリポジトリです

実際には、上記リポジトリをフォークした[masahito-uwamichi/nook](https://github.com/masahito-uwamichi/nook)を定期的に実行しています

# 使用方法

## このリポジトリをフォーク

## github actions secretsを設定

リポジトリのsetting>Secrets and Variables>Actions から

secretsに以下を追加:
- GEMINI_API_KEY
- REDDIT_CLIENT_ID
- REDDIT_CLIENT_SECRET
- REDDIT_USER_AGENT
- EMAIL
- USER_NAME
- NGROK_AUTH_TOKEN

## リポジトリのアクセス権限を変更

リポジトリのsetting>Actions>General から
Workflow Permissionsを「Read and write permissions」にしてSave

## (optional) Actions から Run nook action を実行

日本時間午前９時ごろに定期実行されるので、その他の必要に応じて実行

Geminiのトークンを消費するので、実行しすぎには注意

## Action から Run FastAPI server for 60 minutes を実行

60分間、収集結果を見る & Geminiにフォローアップの質問を投げるためのサーバーがホストされる

## Action のログにあるアクセス用URLからサーバーにアクセス

Ngrokの公開URLアクセスにアクセスしますか？という確認が入るので、そのまま通過する

