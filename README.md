# わせがく専用 AI ART DIRECTOR

わせがく高等学校の広報物制作を想定した、ブラウザ完結型のAIアートディレクションツールです。

## GitHub Pagesで公開する方法

1. GitHubで新しいRepositoryを作成します。
2. このフォルダ内の `index.html` と `assets/wasegaku-logo.png` をRepositoryへアップロードします。
3. Repositoryの **Settings → Pages** を開きます。
4. **Deploy from a branch** を選択します。
5. Branchを `main`、Folderを `/ (root)` にして保存します。
6. 数分後、GitHub Pagesの公開URLからアクセスできます。

## 構成

- `index.html` — Webページ本体
- `assets/wasegaku-logo.png` — 指定されたわせがく高等学校ロゴ

## デザイン固定ルール

主要色は次の3色です。

- GREEN `#176B45`
- DARK `#202A25`
- RED `#C82132`

ロゴは `assets/wasegaku-logo.png` を使用します。

## 注意

このツールの最終成果物は画像そのものではなく、画像生成AIへ渡すための完成版プロンプトです。
