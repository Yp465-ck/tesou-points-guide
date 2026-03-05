# 手相鑑定ポイント早見一覧表

リンクを知っている人のみがアクセスできる補足資料です。

## デプロイ手順

### 1. GitHub にリポジトリを作成

1. GitHub で新規リポジトリ `tesou-points-guide` を作成
2. このフォルダを push:

```bash
cd tesou-points-guide
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/tesou-points-guide.git
git push -u origin main
```

### 2. Vercel でデプロイ

1. [Vercel](https://vercel.com) にログイン
2. **Add New** → **Project**
3. 上記で作成した `tesou-points-guide` リポジトリをインポート
4. **Deploy** をクリック

### 3. 公開URL

デプロイ後、次のURLでアクセスできます:

```
https://[プロジェクト名].vercel.app/x7k2m9p/
```

- ルート (`/`) にアクセスすると 404 になります（意図した動作）
- このURLを共有する人だけが早見表を閲覧できます
