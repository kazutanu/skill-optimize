# skill-optimize-bpk (v2.0.0)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Architecture: 4--Pillar%20BPK%20Pipeline](https://img.shields.io/badge/Architecture-4--Pillar%20BPK%20Pipeline-green.svg)](#4-pillar-bpk-suite-specification)
[![Version: 2.0.0](https://img.shields.io/badge/Version-2.0.0-orange.svg)](#overview)
[![Python: 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)

> Deterministic Autonomous Multi-Agent Orchestration & Skill Optimization Suite (v2.0.0).  
> Grounded in 4 proven historical archetypes: strategic premise audit, modular architecture, dual-phase logistics, and mathematical minimal-diff execution.

---

## ⚡ Overview

`skill-optimize-bpk` (v2.0.0) is a deterministic, fully autonomous multi-agent orchestration framework. By modeling four quintessential roles from history, it establishes an unblocked pipeline that moves from requirement validation to test verification without manual intervention.

```text
[User Task / Strategic Goal]
    │
    ▼ Gate 0: Liu Ji (Premise Audit & Scope Freeze)
[Verify core premises, eliminate bloated requirements, gate invalid tasks]
    │
    ▼ Gate 1: Kozukenosuke Oguri (Modular Architecture & DAG Engineering)
[Break down tasks into reusable modules & Micro-WBS <= 300,000 tokens]
    │
    ▼ Gate 2: Xiao He (Dual-Phase Logistics & Instant Quota Pass)
[Automatic bypass for <= 300k tokens / Restraint audit for large requests]
    │
    ▼ Gate 3: Masujiro Omura (Targeted Diff Patching & Machine Verification)
[Minimal diffs via replace_file_content -> Automated CI test validation (exit_code == 0)]
    │
    ▼ Gate 4: Xiao He (Actual Metering & Immediate Treasury Refund)
[Measure consumed tokens -> Automatically refund surplus back to ledger]
    │
    ▼ Gate 5: Liu Ji & BPK Optimizer (Final Zero-Base Audit & 2-Tier Compression)
[Prune decorative bloat -> 2-Tier refactoring -> Append 1-line to progress.md]
```

---

## 🏛 4-Pillar BPK Suite Specification

### 1. 🛡 Liu Ji (`liuji-protocol`)
> **日本語**: 明建国の軍師。冷徹な現実主義で誤った前提と過剰設計を排除し、安全な迂回路と最終監査を統制する。
* **Historical Archetype**: Grand Strategist of the Ming Dynasty; renowned for ruthless pragmatism, identifying root causes, and eliminating false premises.
* **Gate 0 (Premise Verification)**: Validates requirements upfront to eliminate unnecessary over-engineering.
* **Safety Gate (Tianji Mediation)**: Automatically intervenes after 2 consecutive errors to enforce fallback routing.
* **Gate 5 (Zero-Base Audit)**: Prunes decorative prose, redundant steps, and structural code bloat before delivery.

### 2. 📐 Kozukenosuke Oguri (`kozukenosuke-bpk`)
> **日本語**: 幕末の勘定奉行。「土蔵」思想に基づき、全モデルで再利用可能なモジュラー設計と30万枠DAG工程を策定する。
* **Historical Archetype**: Magistrate of the Tokugawa Shogunate; designed enduring modern industrial infrastructure ("Storehouse" philosophy).
* **Modular Storehouse Architecture**: Defines standardized, reusable specifications across any LLM without vendor lock-in.
* **300k-Token DAG Breakdown**: Decomposes complex tasks into micro-WBS units strictly bounded to 300,000 tokens.
* **Targeted Diff Specifications**: Generates unambiguous execution specs (`TargetFile`, `LineRange`, `DiffSpec`) directly wired to the executor.

### 3. ⚖ Xiao He (`xiaohe-bpk`)
> **日本語**: 漢建国の功臣第一位。30万枠自動パスで前線を止めず、事後実測により未使用トークンを即座に国庫台帳へ返還する。
* **Historical Archetype**: Founding Prime Minister of the Han Dynasty (Rank 1 Merit); master of continuous frontline supply lines and state registers.
* **Wartime Logistics Mode**: Provides an automatic, zero-friction pass for micro-tasks (<= 300k tokens) to keep execution unblocked.
* **Peacetime Fiscal Restraint**: Automatically downgrades non-critical tasks from high-cost models to cost-efficient models.
* **Real-Time Metering & Refund**: Measures consumed tokens post-execution and immediately returns surplus quota back to the treasury ledger.

### 4. ⚡ Masujiro Omura (`masujiro`)
> **日本語**: 近代日本兵学の祖。感情を排した数学的計算により、最小差分パッチと自動テスト検証で電撃完遂する。
* **Historical Archetype**: Master of Dutch studies and military science; achieved decisive victories through precision mathematics and ballistics.
* **Targeted Diff Patching**: Prohibits full-file rewrites; only applies atomic line-bounded modifications (`replace_file_content`).
* **Objective Machine Verification**: Rejects subjective completion claims; enforces automated test commands and verifies `exit_code == 0`.
* **Max 3-Line Output**: Completely strips conversational pleasantries, returning strictly facts, links, and progress.

---

## 📊 Performance Benchmarks (Estimated)

| Metric | Base (No Skills) | v1.0.0 (2-Tier Modular) | v2.0.0 (4-Pillar Pipeline) | Key Engineering Driver |
| :--- | :--- | :--- | :--- | :--- |
| **Token Savings** | Baseline (0%) | 30 – 50% | **65 – 75%** | Targeted diffs + micro-quotas + surplus refunds |
| **Task Success Rate** | 40 – 55% | 70 – 80% | **92 – 98%** | DAG decomposition + CI test validation + auto-mediation |
| **Execution Speed** | 1.0x (Baseline) | ~1.5x | **2.5x – 3.5x** | Elimination of full-file rewrites + zero-wait autonomous run |
| **Hallucination Rate** | 15 – 25% | 5 – 8% | **< 1.0%** | Upfront premise audit + strict type constraints + machine tests |

---

## 🛠 Directory Structure

```text
skill-optimize/
├── skills/                      # 4-Pillar BPK Skills
│   ├── skill-optimize-bpk/      # v2.0.0 Unified Orchestrator & Optimizer
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
├── scripts/                     # Automated audit & meter scripts
├── references/                  # Compliance guidelines & schemas
└── README.md
```

---

## 💻 CLI & Pipeline Triggers

### 1. Run Autonomous 4-Pillar Pipeline
```bash
# Execute full pipeline: Liu Ji -> Kozukenosuke -> Xiao He -> Masujiro -> BPK Optimizer
agy skill run skill-optimize-bpk --auto-pipeline
```

### 2. Standalone 2-Tier Compression & Domain Adaptation
```bash
# Optimize skill for Legal & Compliance in English
python -m skill_optimize --input input.md --field "Legal, Compliance" --lang "English"

# Optimize skill for Financial Portfolio Management in Japanese
python -m skill_optimize --input input.md --field "Finance, Portfolio" --lang "Japanese"
```

---

## 🛡 Strict Operational Constraints

* ❌ **No Manual Disconnection**: The agent must chain all 4 pillars automatically without asking the user at every step.
* ❌ **No Premise Bypass**: Never modify code without passing Gate 0 premise verification.
* ❌ **No Unverified Claims**: Never report completion without attaching objective test command outputs (`exit_code == 0`).
* ❌ **No Dead Token Hoarding**: Unused budget must immediately be refunded to the treasury ledger.
* ❌ **No Output Bloat**: All conversational terminal responses must be condensed into a maximum of 3 lines.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
