# skill-optimize-bpk (v2.0.0)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Architecture: 4--Pillar%20BPK%20Pipeline](https://img.shields.io/badge/Architecture-4--Pillar%20BPK%20Pipeline-green.svg)](#the-4-pillar-historical-archetypes--engineered-skills)
[![Version: 2.0.0](https://img.shields.io/badge/Version-2.0.0-orange.svg)](#overview)
[![Python: 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)

> Deterministic Autonomous Multi-Agent Orchestration & Skill Optimization Suite (v2.0.0).  
> Grounded in the proven historical archetypes of strategic audit, modular architecture, dual-phase logistics, and mathematical execution.

---

## ⚡ Overview

`skill-optimize-bpk` (v2.0.0) is a deterministic, fully autonomous multi-agent orchestration framework. By modeling four quintessential roles from history, it establishes a zero-latency pipeline that moves from requirement validation to deployment without waiting for manual human intervention.

```text
[User Task / Strategic Goal]
    │
    ▼ Gate 0: Liu Ji (Strategic Premise Audit & Scope Freeze)
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

## 🏛 The 4-Pillar Historical Archetypes & Engineered Skills

Each pillar in the BPK suite translates a proven historical discipline into a strict, programmatic AI agent specification:

### 1. 🛡 Liu Ji (劉伯温 / Liu Bowen) — Strategic Premise Audit & Safety Gate
* **Historical Archetype**: Imperial Grand Strategist and scholar behind the founding of the Ming Dynasty, renowned for ruthless pragmatism, identifying root causes, and stripping away false premises.
* **Engineered Skill (`liuji-protocol`)**:
  * **Gate 0 (Premise Verification)**: Challenges requirements before execution to reject unnecessary over-engineering.
  * **Safety Gate (Tianji Mediation)**: Intervenes automatically after 2 consecutive failures to enforce fallback and safe-mode routing.
  * **Gate 5 (Zero-Base Audit)**: Final pruning of decorative adjectives, redundant steps, and structural bloat before delivery.

### 2. 📐 Kozukenosuke Oguri (小栗上野介) — Modular Architecture & DAG Engineering
* **Historical Archetype**: Chief Financial and Diplomatic Magistrate of the Tokugawa Shogunate, who designed the modern industrial foundations (Yokosuka Shipyard, Western military systems) built to endure beyond regime changes (*"The store may collapse, but the storehouse remains"*).
* **Engineered Skill (`kozukenosuke-bpk`)**:
  * **Modular Storehouse Architecture**: Defines standardized, reusable specifications that work across any LLM model without vendor lock-in.
  * **300k Token DAG Breakdown**: Decomposes complex tasks into micro-WBS DAG units strictly bounded within 300,000 tokens.
  * **Targeted Diff Specifications**: Generates unambiguous execution specs (`TargetFile`, `LineRange`, `MinimalDiff`) directly wired to the executor.

### 3. ⚖ Xiao He (蕭何) — Dual-Phase Logistics & Fiscal Discipline
* **Historical Archetype**: Supreme Founding Prime Minister (Rank 1 Merit) of the Han Dynasty, master of state registers, continuous frontline supply lines, and post-war economic restoration (*"Allowing the people to rest"*).
* **Engineered Skill (`xiaohe-bpk`)**:
  * **Wartime Logistics Mode**: Provides an automatic, zero-friction pass for micro-tasks (<= 300,000 tokens) to keep execution unblocked.
  * **Peacetime Fiscal Restraint**: Automatically downgrades non-critical tasks from high-cost models to cost-efficient models.
  * **Real-Time Metering & Refund**: Runs `zaimusho_meter.py` post-execution and immediately returns unused quota (`ApprovedQuota - Actuals`) back to the shared ledger.

### 4. ⚡ Masujiro Omura (大村益次郎) — High-Speed Minimal-Diff Execution
* **Historical Archetype**: The father of the modern Japanese army, master of Dutch studies, medicine, and military science, who achieved swift, decisive victories with minimal casualties through exact mathematical calculation and ballistics.
* **Engineered Skill (`masujiro`)**:
  * **Targeted Diff Patching**: Strictly prohibits full-file regenerations; only applies atomic line-bounded modifications (`replace_file_content`).
  * **Objective Machine Verification**: Rejects manual completion claims; enforces automated test commands and verifies `exit_code == 0`.
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
