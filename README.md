# 会社案内サイトテンプレート

GitHub Pagesで公開できる、HTML/CSS中心の静的な会社案内サイトです。

## ファイル構成

```text
company-site-template/
├─ index.html          トップページ
├─ company.html        会社概要ページ
├─ service.html        事業内容ページ
├─ css/
│  └─ style.css        共通スタイル
├─ images/             画像配置用フォルダ
└─ README.md           このファイル
```

## 修正すべき箇所

各HTMLファイル内で `TODO:` を検索してください。

主な差し替え箇所:

- TODO:会社名
- TODO:地域名
- TODO:会社のキャッチコピー
- TODO:会社紹介文
- TODO:代表者名
- TODO:所在地
- TODO:電話番号
- TODO:メールアドレス
- TODO:設立年月
- TODO:資本金
- TODO:事業内容概要
- TODO:事業名1
- TODO:事業名2
- TODO:事業名3
- TODO:許認可・資格など

## GitHub Pages公開手順

1. GitHubに新規リポジトリを作成
2. このファイル一式をpush
3. GitHubのリポジトリで `Settings` → `Pages`
4. `Deploy from a branch` を選択
5. Branchを `main`、フォルダを `/root` に設定
6. 数分後に公開URLへアクセス

## 独自ドメインを使う場合

ルートに `CNAME` ファイルを作成し、以下のようにドメイン名だけを記載します。

```text
example.jp
```

その後、DNS側でGitHub Pages向けの設定を行ってください。
