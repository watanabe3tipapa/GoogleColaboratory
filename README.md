# GoogleColaboratory (Archives)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)

概要

このリポジトリは、Jupyter Notebook（.ipynb）ファイルの格納を目的としたディレクトリです。リポジトリ内のノートブックは Google Drive の「Colab Notebooks」ディレクトリと同期して利用することを想定しています。

ホームページ: https://watanabe3tipapa.github.io/GoogleColaboratory/

主な内容

- カテゴリー別の .ipynb ノートブック群（下記「ディレクトリ構成」参照）
- index.qmd / Quarto 関連ファイル
- LICENSE.md（ライセンス情報はこのファイルをご確認ください）

ディレクトリ構成

- `setup/` … Colab の準備
  - BaseGitHub2GoogleColaboratory.ipynb
  - method4colab_ssh.ipynb
- `network/` … ネットワーク
  - telnets_2023_09_07.ipynb
  - telnets_2023−09_07_chat_by_Go.ipynb
  - telnets_2023−09_07_notalk_by_Go.ipynb
- `data/` … データ処理
  - getrails.ipynb
- `llm/` … LLM
  - strata_colab_guide.ipynb
- ルート … index.qmd, _quarto.yml, _site, assets, LICENSE.md

利用上の注意

- setup/method4colab_ssh.ipynb に記載された「ssh を使う方法」については、README 内でも注意がある通り、Google Colaboratory の利用規約により禁止されているとされています。当該ノートブックは技術学習の参考として扱ってください（該当ノートブックの参照: https://github.com/watanabe3tipapa/GoogleColaboratory/blob/main/setup/method4colab_ssh.ipynb）。

履歴・状態

- このディレクトリは (2022-03-15) に Codespaces を利用して編集できるようになった旨の記述があります。
- README に含まれる情報はリポジトリ内のファイルを元にしており、最終更新日時はリポジトリのメタデータをご確認ください。
- リポジトリは "Archives" として整理されています。アーカイブ状態（GitHub の Archive フラグ）はメタデータをご確認ください。

ライセンス

- リポジトリに LICENSE.md が含まれています。具体的なライセンス条件はそのファイルを参照してください。

参照リンク

- リポジトリ・ホームページ: https://watanabe3tipapa.github.io/GoogleColaboratory/
- setup/method4colab_ssh.ipynb（リポジトリ内）: https://github.com/watanabe3tipapa/GoogleColaboratory/blob/main/setup/method4colab_ssh.ipynb
- Colab デモ（バッジ先、外部リポジトリ）: https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb

補足

- この README はリポジトリ内に既にある情報を整理・再構成したものです。利用方法の具体的手順や追加の操作コマンドなどは、各ノートブックや関連ファイルの内容を確認してください。
