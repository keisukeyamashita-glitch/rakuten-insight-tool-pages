---
marp: false
theme: default
paginate: true
style: |
  section {
    font-family: "M PLUS Rounded 1c", "Yu Gothic UI", sans-serif;
    background: linear-gradient(135deg, #fff6fb 0%, #f3f6ff 55%, #f6fff8 100%);
    color: #5d4b73;
    padding: 56px;
  }
  h1, h2 {
    color: #a16ac8;
  }
  strong {
    color: #ff6fb3;
  }
  code {
    background: #ffffffcc;
    border-radius: 8px;
    padding: 0.1em 0.35em;
  }
---

# 楽天インサイト  
## ツール紹介ページ  

**ふんわり公開ガイド** :sparkles:

GitHub Pages で公開するための  
`index.html` だけのリポジトリです。

---

## :ribbon: 初回セットアップ

1. [GitHub](https://github.com/new) で **新規リポジトリ** を作成  
   （例: `rakuten-insight-tool-pages`）
2. README テンプレートは **付けない**
3. このフォルダからリモート追加して push  
   （`YOUR_USER` と `REPO` は置き換え）

```bash
cd "c:\Users\keisuke.yamashita\Documents\Cursor\rakuten-insight-tool-pages"
git remote add origin https://github.com/YOUR_USER/REPO.git
git branch -M main
git push -u origin main
```

---

## :cloud: Pages を有効化

1. GitHub リポジトリで **Settings -> Pages**
2. **Build and deployment** の **Source** で  
   **Deploy from a branch** を選択
3. **Branch** は `main`、フォルダは **`/ (root)`** で Save

数分後に公開されます :star2:

`https://YOUR_USER.github.io/REPO/`

---

## :heartpulse: 内容の更新

`index.html` を編集して、  
`git add` -> `commit` -> `push` で反映できます。

公開反映まで少し時間がかかることがあります。
