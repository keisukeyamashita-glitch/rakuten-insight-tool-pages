# 楽天インサイト ツール紹介（静的ページ）

GitHub Pages で公開するための `index.html` のみのリポジトリです。

## 初回：GitHub に載せて Pages を有効にする

1. [GitHub](https://github.com/new) で **新規リポジトリ** を作成する（例: `rakuten-insight-tool-pages`）。README テンプレートは付けない。
2. このフォルダでリモートを追加してプッシュする（`YOUR_USER` と `REPO` を置き換え）。

```bash
cd "c:\Users\keisuke.yamashita\Documents\Cursor\rakuten-insight-tool-pages"
git remote add origin https://github.com/YOUR_USER/REPO.git
git branch -M main
git push -u origin main
```

3. GitHub のリポジトリで **Settings → Pages** を開く。
4. **Build and deployment** の **Source** で **Deploy from a branch** を選ぶ。
5. **Branch** は `main`、フォルダは **`/ (root)`** を選んで Save。

数分後、次の形式の URL で表示されます（ユーザー名・リポジトリ名で変わります）。

`https://YOUR_USER.github.io/REPO/`

## 内容の更新

`index.html` を編集して `git add` → `commit` → `push` すれば、反映まで少し時間がかかることがあります。
