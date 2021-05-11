---
title: "Oracle Blockchain Platformチュートリアル"
excerpt: "Oracle Blockchain Platform (OBP) を使ってみよう！という人のためのチュートリアルです。各文書ごとにステップ・バイ・ステップで作業を進めて、OBP の基本的な機能、操作やオペレーションについて学習することができます。"
permalink: /blockchain/
layout: single
tags: "Blockchain"
show_excerpts: true
toc: true
---

Oracle Blockchain Platform (OBP) を使ってみよう！という人のためのチュートリアルです。各文書ごとにステップ・バイ・ステップで作業を進めて、OBP の基本的な機能、操作やオペレーションについて学習することができます。

# 1. インスタンスの作成とブロックチェーンネットワークの構成

- **[Oracle Blockchain Platform インスタンスを作成する](/ocitutorials/blockchain/01_1_create_instance/)**  
  Oracle Cloud Infrastructure (OCI) の管理コンソールを利用し、OBP インスタンスを作成します。まずはここから始めましょう。

- **[Participant インスタンスをブロックチェーン・ネットワークに参加させる](/ocitutorials/blockchain/01_2_join_participant/)**  
  OBP はパーミッション型のブロックチェーンプロトコルである Hyperledger Fabric をベースとしたブロックチェーンプラットフォームです。OBP はひとつ～複数のインスタンス（また、OBP 以外の Hyperledger Fabric の Organization）でブロックチェーン・ネットワークを構成することができます。

  ここではふたつの OBP インスタンスでブロックチェーン・ネットワークを構成します。単一の OBP インスタンスのみを使う場合はこの手順はスキップしてください。

# 2. Channel の構成

- **[Channel を作成し、インスタンスおよび Peer ノードを参加させる](/ocitutorials/blockchain/02_1_create_channel/)**  
  Hyperledger Fabric のデータとロジックの共有範囲の制御などのための仕組みである Channel を作成し、その Channel に対してインスタンスと Peer ノードを参加させます。

<br />