# MyMarkdownCSS

GitHub風のMarkdown表示用CSSスタイルシートです。

## 使い方

HTMLファイルでこのCSSを読み込むことで、Markdownで生成されたHTMLにGitHub風のスタイルを適用できます。

### 基本的な使用方法

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="markdown-pdf.css">
</head>
<body>
    <!-- Markdownから生成されたHTMLをここに配置 -->
</body>
</html>
```

### CDNからの読み込み

GitHubのrawコンテンツURLを使用して直接読み込むこともできます：

```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/konbraphat51/MyMarkdownCSS/main/markdown-pdf.css">
```

## 機能

- GitHub風の見出しスタイル
- コードブロックのシンタックスハイライト対応
- 表のスタイリング
- ライト/ダークモード対応
- 日本語フォント最適化（游ゴシック、メイリオ対応）

## サンプル

`example.html`を参照してください。

## ライセンス

このプロジェクトはLICENSEファイルに記載されているライセンスの下で公開されています。
