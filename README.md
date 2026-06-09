# VPSY — Virtual Simulation System for Psychodynamics

A computational model design for **simulating and observing** the dynamics of emotion.

Built on the premise that *complete reproduction of emotion is impossible*,  
VPSY defines the temporal hierarchy of emotion, mood, and feeling as a computable structure —  
designed as a **semi-organic observation tool** made by humans, for humans.

---

## About This Repository

This repository is a structured collection of documents covering VPSY's design philosophy,  
architectural concepts, data type definitions, and implementation analogies.

It is an original computational emotion model built at the intersection of  
philosophy, phenomenology, and engineering.  
The project is currently in the **concept and design phase**.

### How VPSY Differs from Existing Emotion AI

| Dimension | Conventional Emotion AI | VPSY |
|---|---|---|
| Purpose | Recognition and classification of emotion | Simulation and observation of emotional processes |
| Premise | Emotion is reproducible | Complete reproduction of emotion is impossible |
| Structure | Closer to black-box | 7-layer OSI reference model |
| Memory | Static data | Dynamic degradation via lossy compression |
| Unit of extension | Model | Docker container (per individual) |

---

## Background

This concept began during a period when I could barely attend school  
and was suppressing my emotions just to get through each day in a complex home environment.

In the midst of losing the ability to understand my own emotions,  
I asked: *"If there were a system that could simulate emotion,  
could it help people carrying the same kind of weight I was?"*  
That question became the starting point.

I have been developing this concept for **over 10 years**.

Though I attended a correspondence university, I studied philosophy independently —  
drawing from Husserl's phenomenology and Descartes to deepen my thinking  
about the logical structure of time, consciousness, and emotion.  
That work became the backbone of VPSY's architecture.  
I continue to build its technical foundations through my work as an engineer.

---

## Documents

| # | File | Contents |
|---|---|---|
| 1 | [Conceptual Overview](./01_overview.md) | Purpose, positioning, and overall structure of VPSY |
| 2 | [Design Principles](./02_design-principles.md) | Definition and rationale of the simulation-and-observation stance |
| 3 | [7-Layer Emotion Processing Model](./03_layer-model.md) | Hierarchical architecture mapped to the OSI reference model |
| 4 | [Memory Model](./04_memory-model.md) | Huffman coding + Ebbinghaus forgetting curve application |
| 5 | [Communication Model](./05_communication-model.md) | Emotional transmission design via TCP/IP analogy |
| 6 | [Data Type Definitions](./06_data-types.md) | Environment, relationship, and state data types |
| 7 | [DB Table Design](./07_table-design.md) | Draft design of 14 core tables |
| 8 | [Future Topics](./08_future-topics.md) | Unresolved and extended themes under consideration |

---

## Current Status

```
Design phase        : ████████░░  In progress
Prior research sync : ████░░░░░░  Ongoing
Implementation      : ░░░░░░░░░░  Not yet started
```

This repository contains design and conceptual documentation only.  
No implementation code is included at this stage.

---

## License

[CC BY-SA 4.0](./LICENSE)

When citing, adapting, or redistributing, please credit the original author  
and apply the same license.

---

## Disclaimer

The descriptions in this document are design concepts only.  
They are not intended as medical, clinical, diagnostic, treatment, or advisory content.  
References to state data types are definitions for social-scientific and  
psychiatric simulation targets; they are not intended as direct engagement  
with or diagnosis of any individual.

---

---

# VPSY — Virtual Simulation System for Psychodynamics（日本語）

感情の動きを「模倣し、観察する」ための計算モデル設計構想です。

「感情を完全に再現することは不可能である」という前提に立ち、  
感情・気分・気持ちの時間階層を計算可能な構造として定義し、  
人間が人間のために使う **半有機的な観察ツール** として設計します。

---

## このリポジトリについて

本リポジトリは、VPSYの設計思想・アーキテクチャ構想・データ型定義・  
実装アナロジーを体系的に記述したドキュメント群です。

哲学・現象学・工学の知見を重ねながら構築してきた独自の計算感情モデルであり、  
現時点では **構想・設計フェーズ** にあります。

### 既存の感情AI・感情分析システムとの違い

| 観点 | 一般的な感情AI | VPSY |
|---|---|---|
| 目的 | 感情の認識・分類 | 感情プロセスの模倣と観察 |
| 前提 | 感情は再現可能 | 感情の完全再現は不可能 |
| 構造 | ブラックボックス寄り | OSI参照モデル対応7層 |
| 記憶 | 静的データ | 非可逆圧縮による動的劣化 |
| 拡張単位 | モデル | Dockerコンテナ（個人単位） |

---

## 構想の背景

この構想は、学校にはほとんど通えず、複雑な家庭環境のなかで感情を押し殺して  
生活していた時期に考え始めたものです。

感情が理解できなくなるという感覚の中で、「もし感情をシミュレートできる仕組みがあれば、  
自分のような苦しさを抱える人の一助になるのではないか」という問いが出発点になりました。

以来 **10年以上にわたって考察を続けてきた構想** です。

大学は通信制でしたが、そのなかで哲学を独学し、フッサールの現象学やデカルトの思想から  
時間・意識・感情の論理構造についての考察を深め、VPSYのアーキテクチャの骨格を  
作り上げました。現在はエンジニアとして働くなかで技術的な裏付けを積み上げています。

---

## ドキュメント

| # | ファイル | 内容 |
|---|---|---|
| 1 | [概念全体の地図](./01_overview.md) | VPSYの目的・位置づけ・全体構造 |
| 2 | [設計思想と哲学的立場](./02_design-principles.md) | 模倣・観察という立場の定義と根拠 |
| 3 | [感情処理7層モデル](./03_layer-model.md) | OSI参照モデル対応の階層アーキテクチャ |
| 4 | [記憶モデル](./04_memory-model.md) | ハフマン符号化＋エビングハウス応用 |
| 5 | [通信・伝達モデル](./05_communication-model.md) | TCP/IPアナロジーによる感情伝達設計 |
| 6 | [データ型定義](./06_data-types.md) | 環境・関係性・状態データタイプ |
| 7 | [DBテーブル設計案](./07_table-design.md) | 主要14テーブルの設計案 |
| 8 | [未考察・拡張テーマ](./08_future-topics.md) | 考察中・未解決の拡張テーマ群 |

---

## 現在のステータス

```
設計フェーズ    : ████████░░  進行中
先行研究照合    : ████░░░░░░  継続中
実装           : ░░░░░░░░░░  未着手
```

本リポジトリは設計・構想フェーズのドキュメントです。  
実装コードは含まれていません。

---

## ライセンス

[CC BY-SA 4.0](./LICENSE)

引用・改変・再配布の際は原著者の表示と同一ライセンスの適用をお願いします。

---

## 免責事項

本ドキュメントに含まれる記述は設計構想であり、  
医学的・臨床的な診断・治療・助言を目的とするものではありません。  
状態データタイプ等の記述は、社会科学・精神医学的シミュレーション対象の定義であり、  
当事者への直接的な関与や診断を意図しません。
