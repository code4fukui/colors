# colors

このリポジトリは、[CSS Color Module Level 3](https://www.w3.org/TR/css-color-3/)で指定された140色の名前付きWebカラーのデータセットを提供します。データはCSV、JSON、CBOR形式で利用可能です。

## 利用可能な形式

カラーデータは以下のファイルで提供されています。

- [`webcolor.csv`](webcolor.csv)
- [`webcolor.json`](webcolor.json)
- [`webcolor.cbor`](webcolor.cbor)

## データ構造

各カラーエントリは、`name`（文字列）とそれに対応する16進数の`color`コード（文字列）で構成されています。

**例（JSON）:**
```json
[
  {
    "name": "aliceblue",
    "color": "#f0f8ff"
  },
  {
    "name": "antiquewhite",
    "color": "#faebd7"
  }
]
```

## ライセンス

本プロジェクトは MIT License の下で公開されています。
