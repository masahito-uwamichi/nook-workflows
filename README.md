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

## リポジトリのアクセス権限を変更

リポジトリのsetting>Actions>General から
Workflow Permissionsを「Read and write permissions」にしてSave

