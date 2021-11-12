---
layout: page
title: LC4RIツール(ja)
permalink: /tools_ja/
comments: true
---

Literate Computing Toolsは、以下の目標を達成するためにJupyterを強化するためのものです。

- 自分がどこを操作しているのかを意識させる: セルを状態に応じて色分けすることで、どの操作が進行中でどの操作が成功したのかを確認しやすくします。水色、緑色、ピンクはそれぞれ「実行中」、「正常に終了」、「エラーで終了」を表しています。
- 操作ミスの防止: 一度実行されたセルは、その後の実行に対して「凍結」されます。凍結されたセルは、凍結が解除されるまで実行も編集もできません。
- 見通しの良いオペレーション: Collapsible Headingsの拡張として、その下にある折りたたまれたコードセルをレンガの形で表現しました。レンガの数は操作の複雑さを表しています。さらに、ワンクリックでレンガ（折りたたまれたコードセル）全体を実行することができます。また、レンガの色の変化が進捗状況を表します。
- トレーサビリティの確保: インフラの運用では、大量の実行結果出力が発生します。LC_wrapperカーネルは出力内容を要約し、同時に全ての出力を実行毎にタイムスタンプ付きの個別ファイルに保存します。総出力量を調べたり、過去の結果と比較して検討することができます。


# デモ環境を試す

我々のツールをインストールした「全部入りイメージ」を [Jupyter-LC_docker](https://github.com/NII-cloud-operation/Jupyter-LC_docker) リポジトリで公開しています。
以下のコマンドで8888番ポートにてNotebookサーバーを起動できます。

```
docker run -it --rm -p 8888:8888 niicloudoperation/notebook:latest
```

<iframe src="https://ghbtns.com/github-btn.html?user=NII-cloud-operation&repo=Jupyter-LC_docker&type=star&count=true" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

起動メッセージに表示された認証トークンを使って、ノートブックサーバーにログインすることができます。

## Jupyter拡張

LC4RIの実践のために開発したJupyter拡張は全てOSSとして公開しています。

### [LC_run_through Extension](https://github.com/NII-cloud-operation/Jupyter-LC_run_through)

<iframe src="https://ghbtns.com/github-btn.html?user=NII-cloud-operation&repo=Jupyter-LC_run_through&type=star&count=true" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

{% include youtube.html content='pkzE_nwtEKQ' %}

### [LC_wrapper Kernel](https://github.com/NII-cloud-operation/Jupyter-LC_wrapper)

<iframe src="https://ghbtns.com/github-btn.html?user=NII-cloud-operation&repo=Jupyter-LC_wrapper&type=star&count=true" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

{% include youtube.html content='-28XG7aHYY8' %}

### その他の拡張

- [multi_outputs](https://github.com/NII-cloud-operation/Jupyter-multi_outputs)
- [nblineage](https://github.com/NII-cloud-operation/Jupyter-LC_nblineage)
- [Jupyter-LC_index](https://github.com/NII-cloud-operation/Jupyter-LC_index)
- [sidestickies](https://github.com/NII-cloud-operation/sidestickies)
- [nbsearch](https://github.com/NII-cloud-operation/nbsearch)

## LC4RI実践用環境

LC4RI実践のための環境をまとめています。

- [OperationHub](https://github.com/NII-cloud-operation/OperationHub)

## LC4RI実践Notebook

LC4RIの実践例として各種Notebookをまとめています。

- [Literate-computing-Basics](https://github.com/NII-cloud-operation/Literate-computing-Basics)
- [Literate-computing-Hadoop](https://github.com/NII-cloud-operation/Literate-computing-Hadoop)
- [Literate-computing-Elasticsearch](https://github.com/NII-cloud-operation/Literate-computing-Elasticsearch)
