# GitHub実践入門

## Survey
- 目次を見る
- 学びたい内容3つ書く
  - GitHubのプルリクエストあたりの概念
  - GitFlow
  - Travis CI
- 1つ選んで読む
  - GitFlow
    - 常にリリースする。デプロイは完全に自動化
- 全体の調査
  - 20pごと
  - 1文のみ
  - 目次など
  - 図・グラフ

## Question
- 本の内容を予測する
  - Gitの基本操作＋プルリクエスト＋GitFlow
- 目次を質問にする
  - 自分の予測
  - PullRequestとは？
  - PullRequestを送る手順は？
  - Forkとは？
  - GitFlowとは？
  - GitFlowの大まかな流れは？
  - GitFlowでデプロイする際に使うツールは？

## Read
- 答え合わせ（回答を作る）
### 第1章
- GitHubとはGitのリポジトリホスティングサービス
- PullRequest、GFM(GitHub Flavored Markdown)
### 第2章
- Gitは分散型バージョン管理システム
- Gitのインストール
  - Windowsのみ。Mac、Linuxはデフォルトでインストール済み。
  - 名前・メールアドレスを設定しておく
### 第3章
- GitHubアカウント作成
- Gravatarの設定
- SSH Keyの登録
- リポジトリの作成
### 第4章
- 基本操作
  - git init
  - git status
  - git add
  - git commit
  - git log
- ブランチ
  - git branch
  - git checkout
  - git reset --hard
  - git reflog
  - コンフリクト
  - git commit --amend
  - git rebase
- リモートリポジトリ
  - git remote add
  - git push
  - git clone
  - git pull
  - git fetch
### 第5章
- GitHubリポジトリ
  - Watch/Start/Fork
  - t
  - 歴史の閲覧
  - 差分の閲覧
    - リポジトリ名/compare/比較A...比較B
    - master@{7.day.ago}...master
    - master@{yyyy-mm-dd}...master
- Issue
  - GFM
    - タスクリスト記法
  - Labels
  - Milestone
  - テンプレートやガイドライン
    - ISSUE_TEMPLATE.md
    - CONTRIBUTING.md
    - PULL_REQUEST_TEMPLATE.md
  - コミットメッセージ
    - #id
    - close
- Pull Request
  - Conversation
  - Commits
  - Files changed
    - インラインコメント
- Wiki
- Insights
### 第6章
- GitHubPages
- Fork
  - clone
  - branch
  - commit
  - push
- WIP(Work In Progress)
- Pull Requestの時のメンテナンス
  - remote add upstream
  - fetch upstream
  - merge upstream/master
### 第7章
- Pull Requestを受け取る
  - コードレビュー
  - 画像
    - 2-up
    - Swipe
    - Onion Skin
    - Difference
  - 自分の環境で確認
    - clone, pullなどで更新
    - remote add pr_user url
    - git fetch pr_user
    - git chechout -b test_branch pr_user/pr_branch
    - 確認
    - git branch -D test_branch
### 第8章
スキップ
### 第9章
- GitHub Flow
  - master -> branch -> pull request
  - masterは常にデプロイできる状態に保つ
  - ブランチの命名は明確に
  - 定期的にPush
  - 困ったらPullRequest
  - デプロイは完全自動化
  - テストも自動化
  - PullRequestは小さく
- Git Flow
  - A successful Git branching model

### 第10章
スキップ

## Respond
- 要約する
  - 全体＋3つ
  - Connecting
  - 図解

## Record
- 要約した内容と本の内容を照会する

## Review
- 要約を確認する
- 後日再度確認する
