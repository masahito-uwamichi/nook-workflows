[![Run main.py in Container](https://github.com/masahito-uwamichi/nook-workflows/actions/workflows/run-main.yml/badge.svg)](https://github.com/masahito-uwamichi/nook-workflows/actions/workflows/run-main.yml)

[![Run nook action](https://github.com/masahito-uwamichi/nook-workflows/actions/workflows/run-nook.yml/badge.svg)](https://github.com/masahito-uwamichi/nook-workflows/actions/workflows/run-nook.yml)

# nook-workflows
umiyuki:nookを定期的に実行するワークフローを試しに作ってみるリポジトリです

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

