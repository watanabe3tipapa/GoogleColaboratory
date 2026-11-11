# Google Colaboratory Archives

Google Colab で使用したノートブックと技術ガイドを、用途ごとに整理して公開しているアーカイブです。
ノートブックはそのまま Colab で開いて実行できます。

**公開サイト:** https://watanabe3tipapa.github.io/GoogleColaboratory/

## 収録コンテンツ

| カテゴリー | コンテンツ | 内容 | リンク |
|---|---|---|---|
| setup | [BaseGitHub2GoogleColaboratory.ipynb](setup/BaseGitHub2GoogleColaboratory.ipynb) | GitHub 上のノートブックを Colab から直接開くための下準備 | [開く](https://colab.research.google.com/github/watanabe3tipapa/GoogleColaboratory/blob/main/setup/BaseGitHub2GoogleColaboratory.ipynb) |
| setup | [method4colab_ssh.ipynb](setup/method4colab_ssh.ipynb) | Colab に SSH 接続する方法（現在は利用規約で禁止／学習用） | [開く](https://colab.research.google.com/github/watanabe3tipapa/GoogleColaboratory/blob/main/setup/method4colab_ssh.ipynb) |
| network | [telnets_2023_09_07.ipynb](network/telnets_2023_09_07.ipynb) | インターネット公告（シンプル版） | [開く](https://colab.research.google.com/github/watanabe3tipapa/GoogleColaboratory/blob/main/network/telnets_2023_09_07.ipynb) |
| network | [telnets_2023−09_07_chat_by_Go.ipynb](network/telnets_2023−09_07_chat_by_Go.ipynb) | インターネット公告（チャット版） | [開く](https://colab.research.google.com/github/watanabe3tipapa/GoogleColaboratory/blob/main/network/telnets_2023%E2%88%9209_07_chat_by_Go.ipynb) |
| network | [telnets_2023−09_07_notalk_by_Go.ipynb](network/telnets_2023−09_07_notalk_by_Go.ipynb) | インターネット公告（発話なし版） | [開く](https://colab.research.google.com/github/watanabe3tipapa/GoogleColaboratory/blob/main/network/telnets_2023%E2%88%9209_07_notalk_by_Go.ipynb) |
| data | [getrails.ipynb](data/getrails.ipynb) | 都道府県の鉄道路線を探査し、駅名と緯度・経度を取得 | [開く](https://colab.research.google.com/github/watanabe3tipapa/GoogleColaboratory/blob/main/data/getrails.ipynb) |
| llm | [strata_colab_guide.ipynb](llm/strata_colab_guide.ipynb) | Colab 上で Strata 推論エンジンを動かし、OpenAI 互換 API で利用 | [開く](https://colab.research.google.com/github/watanabe3tipapa/GoogleColaboratory/blob/main/llm/strata_colab_guide.ipynb) |
| mcp | [colab-mcp-cms-guide.html](mcp/colab-mcp-cms-guide.html) | Colab MCP Server を Web 公開し、PWA から CMS を構成するガイド | [読む](mcp/colab-mcp-cms-guide.html) |
| mcp | [colab_mcp_marimo_pwa_architecture.html](mcp/colab_mcp_marimo_pwa_architecture.html) | Colab MCP × marimo × PWA の連携アーキテクチャ調査 | [読む](mcp/colab_mcp_marimo_pwa_architecture.html) |
| mcp | [pwa-colab-connection-guide.html](mcp/pwa-colab-connection-guide.html) | PWA から Colab の GPU / TPU を活用する接続ガイド | [読む](mcp/pwa-colab-connection-guide.html) |
| mcp | [colab_mcp_cms_guide.ipynb](mcp/colab_mcp_cms_guide.ipynb) | CMS ガイドのノートブック版 | [開く](https://colab.research.google.com/github/watanabe3tipapa/GoogleColaboratory/blob/main/mcp/colab_mcp_cms_guide.ipynb) |
| mcp | [colab_mcp_marimo_pwa_architecture.ipynb](mcp/colab_mcp_marimo_pwa_architecture.ipynb) | marimo × PWA 調査のノートブック版 | [開く](https://colab.research.google.com/github/watanabe3tipapa/GoogleColaboratory/blob/main/mcp/colab_mcp_marimo_pwa_architecture.ipynb) |
| mcp | [pwa_colab_connection_guide.ipynb](mcp/pwa_colab_connection_guide.ipynb) | PWA 接続ガイドのノートブック版 | [開く](https://colab.research.google.com/github/watanabe3tipapa/GoogleColaboratory/blob/main/mcp/pwa_colab_connection_guide.ipynb) |
| mcp | [colab_gui_desktop.ipynb](mcp/colab_gui_desktop.ipynb) | 仮想デスクトップ＋ブラウザ自動化デモ | [開く](https://colab.research.google.com/github/watanabe3tipapa/GoogleColaboratory/blob/main/mcp/colab_gui_desktop.ipynb) |
| verification | [houritsu_git.ipynb](verification/houritsu_git.ipynb) | e-Gov 法令検索 API から法令データを取得し、施行日ごとの Git 履歴として再構築する検証 | [開く](https://colab.research.google.com/github/watanabe3tipapa/GoogleColaboratory/blob/main/verification/houritsu_git.ipynb) |

## ディレクトリ構成

```text
.
├── setup/     Colab の準備（接続・SSH）
├── network/   ネットワーク（インターネット公告）
├── data/      データ処理（路線・駅名）
├── llm/       LLM（Strata）
├── mcp/       MCP / 自動化（技術ガイド・GUI デスクトップ）
├── verification/ 検証（法令データ × Git 履歴）
├── assets/    サイト用画像
├── index.qmd  サイトのトップページ
├── _quarto.yml
├── _site/     Quarto のビルド成果物（GitHub Pages で公開）
└── LICENSE.md
```

## 使い方

1. 上の表、または[公開サイト](https://watanabe3tipapa.github.io/GoogleColaboratory/)からコンテンツを選びます。
2. ノートブックは「開く」で Google Colab が起動します。技術ガイドは「読む」でページが開きます。
3. ノートブックはメニューの「ランタイム」→「すべてのセルを実行」で上から順に実行します。

> ノートブックによっては GPU の利用や大容量のディスク空き容量が必要です。各ノートブック冒頭の説明を確認してください。

## サイトのビルド

このリポジトリのサイトは [Quarto](https://quarto.org/) で生成しています。

```bash
# 初回のみ
brew install quarto   # または公式インストーラー

# プレビュー（ローカルサーバー起動）
quarto preview

# ビルド（_site/ に出力）
quarto render
```

`main` ブランチへ push すると、GitHub Actions が `_site/` を GitHub Pages へデプロイします。

## 注意事項

- **`setup/method4colab_ssh.ipynb` の SSH 接続は、Google Colaboratory の利用規約により禁止されています。** 技術学習の参考としてのみ扱い、実際の運用には使用しないでください。
- `llm/strata_colab_guide.ipynb` はモデルのダウンロードに約 70 GB の空き容量を使用します。GPU（L4 / A100 推奨）の利用料金にもご注意ください。
- ノートブックの実行によって生じた結果・損害について、作者は責任を負いません。

## ライセンス

[MIT License](LICENSE.md) — Copyright (c) 2021 Toru Watanabe
