# Resonate EQ

ブラウザで使える 5〜31 バンドのグラフィックイコライザー。

## 公開手順（GitHub Pages）

1. `index.html` 内の `__SITE_URL__`（検索で全件）を、末尾スラッシュ付きの公開URLに置換
   例: `https://ユーザー名.github.io/リポジトリ名/`
2. このフォルダの中身をリポジトリ直下にアップロード（`main` ブランチ）
3. **Settings → Pages → Build and deployment**
   Source: **Deploy from a branch** / Branch: **main** / Folder: **/ (root)** → Save
4. 数分後に公開URLで開けます

## ファイル

| ファイル | 役割 |
| --- | --- |
| `index.html` | アプリ本体（アイコン・マニフェスト内蔵） |
| `sw.js` | オフライン用 Service Worker |
| `ogp.png` | SNS共有用の画像（1200×630） |
| `.nojekyll` | Jekyll処理を無効化 |

## 更新するとき

`index.html` 内の `APP_VER` を上げてアップロードすると、利用中の端末に更新バナーが出ます。
