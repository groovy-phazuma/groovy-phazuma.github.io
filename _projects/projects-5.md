---
title: "[Personal] PAM_Cython: Pachinko Allocation Model (PAM) with Cython"
excerpt: "PAMをCythonで実装して高速化しました。 <br/><br/> <img src='/images/PAM_abstract.png' width=500><br/>"
collection: projects
---

トピックモデルとは、文章データの潜在的なトピックを推定する確率モデルです。
本モデルを用いることで、以下のような情報が得られます。

- トピックに基づく文章のクラスタリング
- ある文章を構成するトピックの寄与（document-topic distribution）
- あるトピックを構成する単語の寄与（topic-word distribution）
今回はあえてPachinko Allocation Model (PAM; パチンコ配分法) というマイナー手法に焦点を当て、実装に取り組みました。

[Qiitaの投稿](https://qiita.com/groovy-phazuma/items/df402e78ad49ad8056a0)もご覧ください。

The source code is available at [https://github.com/groovy-phazuma/PAM_Cython](https://github.com/groovy-phazuma/PAM_Cython).