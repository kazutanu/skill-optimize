# skill-optimize-bpk (v2.0.0)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Architecture: 4--Pillar%20BPK%20Pipeline](https://img.shields.io/badge/Architecture-4--Pillar%20BPK%20Pipeline-green.svg)](#architecture)
[![Version: 2.0.0](https://img.shields.io/badge/Version-2.0.0-orange.svg)](#overview)
[![Python: 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)

> Deterministic Autonomous Multi-Agent Orchestration & Skill Optimization Suite (v2.0.0).

---

## ⚡ Overview & 4-Pillar Architecture

`skill-optimize-bpk` (v2.0.0) は、歴史上の卓越した4つの役割モデル（前提監査・規格設計・二相兵站・数理実行）を現代のAIエージェント開発パイプラインへ昇華させた自律協調スイートです。

単一トリガーにより、過剰な会話や指示待ちを挟むことなく、設計から監査までを最短工数・最小トークンで完遂します。

```text
[Strategic Goal / Task Input]
    │
    ▼ Gate 0: Liu Ji (前提査問 & スコープ凍結)
[Audit premise, eliminate over-engineering & invalid assumptions]
    │
    ▼ Gate 1: Kozukenosuke (土蔵モジュラー設計 & DAG/Micro-WBS)
[Standardized modular breakdown <= 300k tokens, generate DiffSpecs]
    │
    ▼ Gate 2: Xiao He (二相兵站供給 & 30万枠自動パス)
[Instant pass <=300k / Tight fiscal audit >300k / Barrier control]
    │
    ▼ Gate 3: Masujiro (急所一撃実行 & 機械検品)
[Minimal diff (replace_file_content) -> Automated test verification (exit_code == 0)]
    │
    ▼ Gate 4: Xiao He (実測自動決算 & 不用額即時返納)
[Measure actual token logs -> Refund surplus directly to treasury ledger]
    │
    ▼ Gate 5: Liu Ji & BPK (最終冷徹監査 & 2-Tier最適化 & DRAM同期)
[Final zero-base audit -> 2-Tier compression -> Append 1-line to progress.md]
```

---

## 🚀 4-Pillar Pipeline Components

| Component | Historical Archetype | Role & Engineering Discipline |
| :--- | :--- | :--- |
| **`liuji-protocol`** | **劉基 (Liu Ji)** | **軍師・前提監査 & セーフティゲート**<br>・着手前の前提査問と無駄タスクの門前払い<br>・障害時（エラー2回）の天機調停（縮退・迂回）<br>・納品直前の贅肉コード・過剰仕様の削ぎ落とし |
| **`kozukenosuke-bpk`** | **小栗上野介 (Kozukenosuke)** | **SE・土蔵モジュラー設計 & DAG工程策定**<br>・一過性を排した標準規格準拠のモジュール設計<br>・30万トークン以内粒度のMicro-WBS分割<br>・急所差分指示書（DiffSpec）の自動生成 |
| **`xiaohe-bpk`** | **蕭何 (Xiao He)** | **財務・二相兵站 & 予算決算統制**<br>・前線を止めない30万枠自動兵站パス<br>・上限防壁（150万トークン）による破綻防止<br>・事後実測による不用額の国庫（台帳）即時返納 |
| **`masujiro`** | **大村益次郎 (Masujiro)** | **実行エンジン・急所一撃 & 機械検品**<br>・全面書換を厳禁した最小差分修正（Diff）<br>・テスト・構文検査による `exit_code == 0` 検証<br>・感情・散文を排した最大3行以内の出力 |
| **`skill-optimize-bpk`** | **BPK Optimizer** | **統合オーケストレーター & 2-Tier最適化**<br>・1トリガーによる4極直列パイプライン実行<br>・内部論理（Tier 1）と遵守事項（Tier 2）の分離圧縮<br>・多言語・動的ドメイン適応（`--field`, `--lang`） |

---

## 🛠 Directory Structure

```text
skill-optimize/
├── skills/                      # 4-Pillar BPK Skills
│   ├── skill-optimize-bpk/      # v2.0.0 Integrated Orchestrator & Optimizer
│   │   └── SKILL.md
│   ├── kozukenosuke-bpk/        # Modular Architecture & DAG Engineering
│   │   └── SKILL.md
│   ├── xiaohe-bpk/              # Dual-Phase Fiscal & Logistics Engine
│   │   └── SKILL.md
│   ├── masujiro/                # Fast & Minimal Diff Execution Engine
│   │   └── SKILL.md
│   ├── token-efficient-architecture/
│   │   └── SKILL.md
│   └── liuji-protocol/
│       └── SKILL.md
├── scripts/                     # Execution & parsing scripts
├── references/                  # Domain-specific constraints & guidelines
└── README.md
```

---

## 💻 Pipeline Triggers & CLI

### 1. 4極統合自律パイプライン（推奨）
```bash
# 全極（小栗→蕭何→大村→劉基/最適化）を一連セットで直列実行
agy skill run skill-optimize-bpk --auto-pipeline
```

### 2. 単体スキル2-Tier最適化・ドメイン適応
```bash
# 法務・コンプライアンス分野へ英語で最適化
python -m skill_optimize --input input.md --field "Legal, Compliance" --lang "English"

# 財務・資産管理分野へ日本語で最適化
python -m skill_optimize --input input.md --field "Finance, Portfolio" --lang "Japanese"
```

---

## 🛡 Anti-Patterns & Strict Constraints

* ❌ **個別手動呼び出し依存の禁止**: ユーザーに各極を手動で1個ずつ実行させる行為を禁止。
* ❌ **前提査問バイパスの禁止**: 劉基ゲートを省いて直接実装に着手する行為を禁止。
* ❌ **未検証完了報告の禁止**: 客観的なテスト実行ログなしに完了とする行為を禁止。
* ❌ **不用額死蔵の禁止**: 実測決算を行わず、余剰トークンを国庫へ返納しない行為を禁止。
* ❌ **3行超え散文出力の禁止**: 端末への出力は要点・リンク・進捗のみ最大3行に凝縮。

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
