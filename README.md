# pattern_based_formal_and_abbr_extraction

法令文中の略称と正式名称を、パターンベースで抽出する方法のRust言語による実装です。

# 使用方法

## 依存ソフトウェア

RustとCargoをインストールする必要があります。

詳しくはこちらに従い、インストールを行ってください。：<https://www.rust-lang.org/learn/get-started>

## git cloneする場合

git clone を行い、`cargo run`で法令文を与えて実行すると解析が行われ、法令文中の略称と正式名称のペアを標準出力に表示します。

```sh
git clone https://github.com/japanese-law-analysis/pattern_based_formal_and_abbr_extraction.git

cd pattern_based_formal_and_abbr_extraction

cargo run -- この法律において「行政機関」とは、個人情報の保護に関する法律（以下「個人情報保護法」という。）第二条第八項 に規定する行政機関をいう。
```

## インストールする場合

Cargoを用いてインストールを行い、法令文を引数に与えて実行します。

```sh
cargo install https://github.com/japanese-law-analysis/pattern_based_formal_and_abbr_extraction.git

pattern_based_formal_and_abbr_extraction この法律において「行政機関」とは、個人情報の保護に関する法律（以下「個人情報保護法」という。）第二条第八項 に規定する行政機関をいう。
```
