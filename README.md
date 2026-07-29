# gakushu-privacy

学習アプリ（gakushu 製品ライン）のプライバシーポリシーを GitHub Pages で公開するためのリポジトリ。

- 公開先: https://lushunm.github.io/gakushu-privacy/
- 本文の原本は private リポジトリ `lushunm/gakushu` の `apps/<app>/privacy.html`。
  **原本を変更したらここにも反映すること**（アプリ内表示と公開ページで内容がずれないようにする）。

## 反映のしかた

**手でコピーしないこと。** 原本側にスクリプトがあるので、その出力で置きかえる。

```
# lushunm/gakushu の中で
node scripts/make-privacy-public.mjs     # docs/privacy-public/ を作りなおす
```

`docs/privacy-public/` の中身（入口ページ＋各アプリ）を、このリポジトリの中身として置きかえる。
公開版は、アプリ内専用の「← アプリにもどる」リンクだけを外した同一内容になる。

## 収録しているアプリ

| アプリ | ページ |
|---|---|
| しゃかいクエスト！（社会科） | [social-studies/privacy.html](social-studies/privacy.html) |
| えいけん5級チャレンジ！ | [eiken-5/privacy.html](eiken-5/privacy.html) |
| えいけん4級チャレンジ！ | [eiken-4/privacy.html](eiken-4/privacy.html) |
| えいけん3級チャレンジ！ | [eiken-3/privacy.html](eiken-3/privacy.html) |
| えいけん準2級チャレンジ！ | [eiken-pre2/privacy.html](eiken-pre2/privacy.html) |
