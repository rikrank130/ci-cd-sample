# github actions を用いた CI/CD デモ

## 目的：

CI/CD（継続的インテグレーション/継続的デリバリー）を用いて、
自動デプロイリリースの基本を抑えて、チームとしてのボトムアップを図る。※1

## メリット：

**作業の簡素化、自動化**、**ヒューマンエラーの減少**、リリース速度の向上、バグの早期発見

-> これまで FTP クライアントでおこなっていた**納品データの手動アップ作業**を自動化することができる。

## Github Actions とは

> GitHub Actions は、ビルド、テスト、デプロイのパイプラインを自動化できる継続的インテグレーションと継続的デリバリー (CI/CD) のプラットフォームです。リポジトリに変更をプッシュするたびにテストを実行するワークフロー、またはマージされた pull request を運用環境にデプロイしたりするワークフローを作成できます。※2

-> これらの仕組みをを用いることで、ソースコード管理をしてなおかつ納品データの自動デプロイが実現できる。

## 構成

1. github actions を使って、簡単なデモを触る
   1. [資料](./github-actions-demo.md)
2. パッケージのインストール　〜　ビルドを自動化する
   1. [資料](./)
3. Astro + AWS S3（Cloud Front）を用いたデモを触る
   1.

## 参考文献：

https://qiita.com/choco_p/items/1bd1b106daee1fbd4449
https://aws.amazon.com/jp/devops/continuous-integration/
https://docs.github.com/ja/actions/quickstart
