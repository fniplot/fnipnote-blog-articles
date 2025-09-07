# フニプさんの趣味ノートの記事を管理するリポジトリ

## 執筆環境

- VS Code
  - 拡張機能
    - WordPress Post

## WordPress Post の設定

コマンドパレット（Ctrl + Shift + P）を開き、「基本設定: ワークスペース設定を開(JSON)/Preferences: Open Workspace Setting(JSON)」と入力し選択します。

設定ファイル（setting.json）が開くので、settings キーに

- wordpress-post.apiUrl: "https://WordPress サイトのドメイン名/wp-json/wp/v2"
- wordpress-post.authUser: "WordPress にログインする時のユーザ名"
- wordpress-post.authPassword: "WordPress の RESTAPI のアプリケーションパスワード"

を追記します。

```
{
  "folders": [
    {
      "path": "../path"
    }
  ],
  "settings": {
    "wordpress-post.apiUrl": "...",
    "wordpress-post.authUser": "...",
    "wordpress-post.authPassword": "..."
  }
}

```

## 投稿方法

コマンドパレット（Ctrl + Shift + P）を開き、「WordPress Post: Post」を選択します。投稿する際は、投稿する記事の Markdown ファイルを開いている状態と、Title を記載してください。投稿することができないためです。

## 運用方法

## 投稿する記事について

投稿する記事について以下を考えています。

- Linux
  - Ubuntu
- プログラミング
  - Python、Javascript、Typescript、PHP、HTML
- フレームワーク
  - Vue.js、Next.js
- IT Tech
  - Git、Docker、生成 AI、Datadog、Slack
- AWS
  - 開発事例（アーキテクチャ）
- VSCode
  - 設定方法を記載
  - 拡張機能開発
- Wordpress
  - 設定方法を記載
  - プラグイン開発
- ゲーム
  - マインクラフトのサーバー運用
  - マインクラフトの Mod 開発
