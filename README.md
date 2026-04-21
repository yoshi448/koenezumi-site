# 声鼠 公開サイト

声鼠の Microsoft Store 提出用に公開する静的サイトです。

## 公開URL

GitHub Pages で次の URL に公開する想定です。

```text
https://yoshi448.github.io/koenezumi-site/
https://yoshi448.github.io/koenezumi-site/privacy.html
https://yoshi448.github.io/koenezumi-site/support.html
```

## 内容

- `index.html`: 声鼠の簡単な紹介
- `privacy.html`: プライバシーポリシー
- `support.html`: サポートページ
- `styles.css`: 共通スタイル

## デプロイ

GitHub の `Settings` → `Pages` で `Source` を `GitHub Actions` にしたうえで、`main` へ push すると `.github/workflows/pages.yml` により公開されます。
