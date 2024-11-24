# 職務経歴書

[![markdown lint](https://github.com/kaz-under-the-bridge/resume/actions/workflows/lint.yaml/badge.svg)](https://github.com/kaz-under-the-bridge/resume/actions/workflows/lint.yaml)
[![PDF](https://github.com/kaz-under-the-bridge/resume/actions/workflows/release.yaml/badge.svg)](https://github.com/kaz-under-the-bridge/resume/actions/workflows/release.yaml)
[![pages-build-deploymen](https://github.com/kaz-under-the-bridge/resume/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/kaz-under-the-bridge/resume/actions/workflows/pages/pages-build-deployment)

## ファイル

- [経歴書 Markdown](https://github.com/kaz-under-the-bridge/resume/blob/main/docs/README.md)
- [GitHub Pages](https://github.com/kaz-under-the-bridge/resume#:~:text=kaz%2Dunder%2Dthe%2Dbridge.github.io/resume/)
- [PDF](https://github.com/kaz-under-the-bridge/resume/releases)

## セットアップ

- go task(task runner)のinstall
[参照](https://taskfile.dev/installation/)

- 周辺ツールのインストール

```bash
cd /$project_root
task install_tools
```

## 編集したら

```bash
task # defaultはlinterのlocal実行と、tag versionを生成してremoteへコードとtagをpushする
```
