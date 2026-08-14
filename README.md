# skill-optimize-bpk (v2.0.0)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Architecture: 4--Pillar%20BPK%20Pipeline](https://img.shields.io/badge/Architecture-4--Pillar%20BPK%20Pipeline-green.svg)](#architecture)
[![Version: 2.0.0](https://img.shields.io/badge/Version-2.0.0-orange.svg)](#overview)
[![Python: 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)

> Autonomous Multi-Agent Orchestration & Deterministic Skill Compression Suite (v2.0.0).

---

## ⚡ Overview & 4-Pillar BPK Pipeline

`skill-optimize-bpk` v2.0.0 integrates the **4-Pillar Autonomous Engineering Suite** under **Liu Ji's Strategic Audit & Safety Gate**:

```text
[Strategic Goal / Task Input]
    │
    ▼ Gate 0: Liu Ji (軍師・前提査問 & スコープ凍結)
[Audit premise, eliminate over-engineering]
    │
    ▼ Gate 1: Kozukenosuke (小栗上野介・土蔵設計 & DAG/Micro-WBS)
[Modular breakdown <= 300k tokens, generate DiffSpecs]
    │
    ▼ Gate 2: Xiao He (蕭何・兵站供給 & 30万枠自動パス)
[Pass <=300k directly / Tight audit >300k / Enforce 1.5M token barrier]
    │
    ▼ Gate 3: Masujiro (大村益次郎・電撃実行 & 機械検品)
[Minimal diff (replace_file_content) -> Automated test verification]
    │
    ▼ Gate 4: Xiao He (蕭何・実測自動決算 & 不用額返納)
[Measure actual tokens -> Surplus refund to treasury ledger]
    │
    ▼ Gate 5: Liu Ji & BPK (冷徹監査 & 2-Tier最適化 & DRAM同期)
[Final audit -> 2-Tier compression -> Append 1-line to progress.md]
```

---

## 🚀 4-Pillar Suite Components

| Component | Historical Archetype | Role | Key Function |
| :--- | :--- | :--- | :--- |
| **`liuji-protocol`** | 劉基（劉伯温） | 軍師・戦略統制 | 前提査問、天機調停（例外エスカレーション）、最終冷徹監査 |
| **`kozukenosuke-bpk`** | 小栗上野介 | SE・設計 | 土蔵モジュラー設計、30万トークン粒度DAG工程、急所指示書 |
| **`xiaohe-bpk`** | 蕭何 | 財務・兵站 | 30万枠自動兵站パス、上限防壁制御、実測決算、不用額返納 |
| **`masujiro`** | 大村益次郎 | 実行エンジン | 最小差分修正、機械検品(`exit_code == 0`)、最大3行出力 |
| **`skill-optimize-bpk`** | BPK Optimizer | 最適化・オーケストレーター | 1トリガー全自動パイプライン連動、2-Tier多言語・ドメイン適応 |

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

### 1. Unified Autonomous Pipeline Trigger
```bash
# Run full 4-Pillar Pipeline (Kozukenosuke -> XiaoHe -> Masujiro -> LiuJi/BPK)
agy skill run skill-optimize-bpk --auto-pipeline
```

### 2. Domain & Language 2-Tier Adaptation
```bash
# Optimize for Legal domain in English
python -m skill_optimize --input input.md --field "Legal, Consent" --lang "English"

# Optimize for Financial asset management
python -m skill_optimize --input input.md --field "Finance, Portfolio" --lang "Japanese"
```

---

## 🛡 Anti-Patterns & Constraints

* ❌ **No Manual Disconnection**: Never require user to invoke each persona manually.
* ❌ **No Premise Bypass**: Never bypass Liu Ji's premise gate before touching code.
* ❌ **No Unverified Completion**: Never declare completion without objective test logs.
* ❌ **No Dead Token Storage**: Always refund unused budget back to treasury.
* ❌ **No Prose Overflow**: Limit all user-facing terminal outputs to max 3 lines.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
