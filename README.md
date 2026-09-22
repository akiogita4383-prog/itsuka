# いつか帳

欲しい・観たい・行きたい・食べたい・作りたいを素早くメモする PWA。

## 公開（GitHub Pages）
1. このフォルダの中身をリポジトリのルートに置いて push
2. Settings → Pages → Branch: main / (root) を選んで Save
3. `https://<ユーザー名>.github.io/<リポジトリ名>/` を開く

## インストール
- iPhone：Safari で開く → 共有 → 「ホーム画面に追加」
- Android：Chrome で開く → メニュー → 「アプリをインストール」

## 更新するとき
`index.html` を変えたら `sw.js` の `VERSION` を上げて push。
アプリを一度閉じて開き直すと新しい版になります。

## データ
メモは端末内（localStorage）に保存されます。
機種変更やURL変更の際は「書き出す」→「読み込む」で移してください。
