# SEN / SxN Manifesto — Draft v1.0
### Structured English Notation → Structured x Notation  
A New Structural Literacy for the AI Era  
© 2026 Toa Saida — SEN Project

---

## Overview
SEN（Structured English Notation）は、英語の構造を可視化するための新しい記法であり、  
その発展形である SxN（Structured *x* Notation）は、  
全ての言語に共通する構造的核を抽出することを目指すプロジェクトです。

本リポジトリは、SEN/SxN の思想・仕様・構造をまとめた  
**公式マニフェスト（Draft v1.0）** を公開するためのものです。

---

## Version
- **Current Release:** Draft v1.0  
- **Status:** 思想・仕様の初版（ドラフト）  
- **Purpose:** オリジナル性の証明と、今後の発展の基盤づくり

---

## Sample Files (Draft)

The repository includes an example SEN file located in  
`samples/example_set_v1_draft.sen`.

This example set is provided as a **Draft** to illustrate the conceptual direction of SEN.  
Its structure, indentation rules, and notation are **provisional** and will be refined  
as the specification evolves.

The purpose of this Draft example is to:

- demonstrate how SEN expresses structural dependencies  
- show how modifiers and nested clauses can be visualized  
- provide a reference for educators and developers during early discussions  
- serve as a prototype before formalizing the notation in the specification  

This file is **not** part of the formal specification and should be treated as an  
exploratory sample.

---

# Manifesto (Draft v1.0)

## 1. SEN は、英語の構造を可視化するための記法である
SEN（Structured English Notation）は、英語の語順を保ちながら、  
修飾関係・節構造・意味の流れを外付けで可視化するための記法である。

これは、漢文読解における **返り点・レ点・送り仮名** に近い発想である。  
漢文は語順が日本語と異なるため、読者は外付けの記号を使って  
「どこを先に読み、どこを後に読むか」を視覚的に理解する。

SEN も同様に、英語の文構造を  
- どこが主線（S + V）か  
- どこが修飾で、どこにかかるのか  
- どの節がどの節を包んでいるのか  

といった形で **外付けの記法として可視化する**。

つまり SEN は、  
**英語を語順のまま構造的に読むための、現代版・英語版の返り点である。**

---

## 2. SEN は、英語読解の「多段階的な圧縮・展開」を可能にする
SEN は、文を **圧縮 → 展開** の二段階で読むだけでなく、  
文の内部に含まれる **入れ子構造（文の中の文、句の中の句）** を  
多段階的に圧縮・展開できる。

- 主線（S + V）だけを抽出して最上位の構造を把握する  
- 修飾句・節を一段階ずつ展開して意味の流れを追う  
- さらに内部の節・句を必要に応じて展開する  
- どの段階でも「どこが幹でどこが枝か」が視覚的にわかる  

この **階層的・再帰的な構造操作** によって、  
英文は単なる線形の文字列ではなく、  
**階層構造を持つ情報として扱えるようになる。**

この多段階構造は、後述する SxN が目指す  
**「全言語に共通する構造的核」** と同じ原理に基づいている。

---

## 3. SEN は、英語教育の現場に“再現性”をもたらす
長年、読解指導は講師の経験と勘に依存してきた。  
SEN は修飾の流れや節構造を視覚化し、説明を標準化し、  
特定の講師の技能に依存しない、構造的で再現性のある読解プロセスを提供する。

---

## 4. SxN は、AI 時代の“共通言語”となる可能性を持つ
SEN は英語の構造を可視化するための記法であるが、  
その発展形である **SxN（Structured *x* Notation）** は、  
あらゆる言語に共通する構造的核を抽出することを目的とする。

AI は曖昧な表現よりも、  
構造が明確で、依存関係が可視化された情報を好む。

SxN の中心核は、  
**全ての言語に共通する構造だけを抽出した表現**となり得る。

この構造的核は、  
人間と AI の双方が理解しやすい“共通言語”として機能し、  
多言語処理・翻訳・プロンプト設計・知識表現の基盤となる可能性を持つ。

---

## 5. SEN は、IT で流通可能な“テキスト型メディアタイプ”である
SEN は単なる学習記法ではなく、  
**機械処理に適した構造化テキスト**として扱える。

- プレーンテキストで表現可能  
- Git やバージョン管理に適合  
- diff が取りやすい  
- 構造を JSON／XML／YAML に変換可能  
- GUI 表示や折りたたみ構造と直結  
- AI モデルの入出力として扱いやすい  

さらに、SEN は **XML のように“スキーマ（schema）で構造を定義できる”**  
メディアタイプとして設計可能である。

- 文の構成要素（S, V, O, 修飾句, 節）を型として定義  
- 依存関係を属性として記述  
- 文法的制約をスキーマで検証可能  
- 自動解析・自動生成・自動整形が可能  

これにより、SEN／SxN は  
**教育・AI・言語処理・知識管理の基盤となる形式言語**としての性質を持つ。

---

## 6. SEN は GUI と結びつくことで“速読ツール”として完成する
SEN が構造化テキスト（第5項）として定義されているため、  
GUI による視覚的な展開・折りたたみが自然に実現できる。

GUI 上では、SEN の構造が次のように直感的に操作できる。

- 主線（S + V）だけを表示して“圧縮読み”を行う  
- 修飾句・節をクリックで展開し“精読”に切り替える  
- 矢印や階層表示で修飾の流れを一目で把握する  
- 英英辞書の長い定義文も折りたたみ構造で読みやすくなる  

これは、従来の速読法のような感覚的・訓練依存の手法ではなく、  
**構造に基づく論理的で再現性のある速読**を実現する。

GUI は SEN の補助ではなく、  
**SEN を速読ツールとして成立させるための必然的なインターフェース**である。

---

## 7. SEN は「楽譜」として機能し、翻訳を介さない“直接理解”を可能にする
SEN は、英文を日本語に翻訳して理解するのではなく、  
**構造そのものを読むことで直接理解する**ための“楽譜”として機能する。

- 主線はメロディ  
- 修飾句はコード  
- 節構造は和声（ハーモニー）  
- 展開・折りたたみは楽曲の構造操作  

この「楽譜としての SEN」によって、  
学習者は英文を **音楽のコード進行を読むように** 理解できる。

これは、翻訳を介さずに  
**英語を英語のまま構造として理解する能力（direct comprehension）**  
を育てる。

この“コード感”は、SxN の中心核とも親和性が高く、  
多言語を構造として直接読むための基盤となる。

---

## 8. SEN は、誰でも使えるが、最終的には“直接理解”へとつながる
SEN は道具であり、誰でも使える。  
しかし、使い続けることで、英文を日本語に翻訳するのではなく、  
**構造そのものを読むことで理解する「直接理解（direct comprehension）」**  
へと自然に移行していく。

これは、SEN を“楽譜”として読み、  
主線・修飾・節構造の流れをコード進行のように捉えることで生まれる感覚である。

SEN の目的は、記法そのものを覚えることではなく、  
**構造をそのまま感じ取り、意味を直接つかむ力**を育てることである。

---

## 9. SEN は、ここから育っていく技術である
SEN は完成形ではなく、これから多くの人の手によって成長していく。

- 教育現場での実用化  
- 出版社による普及  
- 研究者による理論化  
- 開発者によるツール化  
- 多言語化（SxN）による拡張  

SEN は、これから世界に向けて育っていく技術である。

---

# Package Naming Policy (Draft)
SEN Project では、将来の実装・標準化を見据え、  
以下の命名ポリシーを採用します。

## Core Packages
- **`sen`**  
  SEN のコア実装（英語版）

- **`sen-cli`**  
  コマンドラインツール（解析・可視化・検証）

- **`sen-gui`**  
  GUI 実装（折りたたみ・展開・構造表示）

## SxN（多言語版）
- **`sxn`**  
  SxN の中心核（言語非依存の構造定義）

- **`sxn-en`**  
  英語モジュール（SEN 相当）

- **`sxn-ja`**  
  日本語モジュール（将来）

---

## License
© 2026 Toa Saida — SEN Project  
All rights reserved.
