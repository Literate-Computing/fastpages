---
layout: page
title: LC4RIとは？(ja)
permalink: /introduction_ja/
---

Literate Computing for Reproducible Infrastructure（以下 「LC4RI」）は、インフラ運用の場面において **機械的に再現できる、人が読み解ける手順** を手段として、過度に自動化に依存することのない、レジリエントな **人間中心の機械化** をめざしています。そこでは、作業を効率化しつつもブラックボックス化せず、作業に対する理解をチーム内でコミュニケーションできる、また、目的と手段の整合性や限界を理解し議論・評価できると言った場を維持することで、**ノウハウの移転・共有を促し運用者のスキル向上とエンジニアリングチームの再生産**をはかることを重視しています。

多くの現場では、管理サーバにログインしコンソール上で作業を行う、作業内容や証跡はWiki等に随時転記して共有する.. といった形態が一般的と思います。これに対しLC4RIでは運用管理サーバ上にNotebookサーバを配備し、作業単位毎にNotebookを作成、作業内容やメモを記述しながら随時実行するといった作業形態を推奨しています。作業の証跡を齟齬なく記録する仕組み、過去の作業記録を参照して機械的に再現あるいは流用できる仕組み、機械的に実行できるとともに人が読み解き補完することもできるNotebook手順を整備しています。

## Jupyter拡張

- [Python2/Python3 kernel with LC_wrapper](https://github.com/NII-cloud-operation/Jupyter-LC_wrapper)
- [multi_outputs](https://github.com/NII-cloud-operation/Jupyter-multi_outputs)
- [run_through](https://github.com/NII-cloud-operation/Jupyter-LC_run_through)
- [nblineage](https://github.com/NII-cloud-operation/Jupyter-LC_nblineage)
- [i18n_cells](https://github.com/NII-cloud-operation/Jupyter-i18n_cells)

[ツールの詳細](../tools_ja/)