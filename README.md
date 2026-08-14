# skill-optimize-bpk

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Architecture: 2-Tier](https://img.shields.io/badge/Architecture-2--Tier%20Modular-green.svg)](#architecture)
[![Version: 1.0.1](https://img.shields.io/badge/Version-1.0.1-orange.svg)](#overview)
[![Python: 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)

> Deterministic AI Agent Skill (.md) compression & domain adaptation engine via Flexible 2-Tier Architecture (v1.0.1).

---

## ⚡ Overview

`skill-optimize-bpk` is an optimization engine designed to refactor and compress LLM/Agent skill files (`SKILL.md`). It decouples internal execution logic from localized domain terms, achieving significant token efficiency while strictly preserving regulatory compliance and verbatim domain language.

```text
Raw Skill (.md)
│
├──▶ Multi-Persona Review (Expert / Systems Engineer / End-User)
├──▶ 2-Tier Refactoring (Tier 1: Control Flow | Tier 2: Domain Terms)
└──▶ LiuJi Audit Protocol (Premise Verification & Zero-Base Pruning)
│
▼
Optimized SKILL.md (Token-Efficient, Grounded & Production-Ready)
```

---

## 🚀 Key Features

* **Flexible 2-Tier Architecture**:
  * **Tier 1 (Internal Logic)**: Optimized pseudo-code, isolated system variables, and strict conditional syntax.
  * **Tier 2 (Compliance & Language)**: Verbatim term protection for legal, administrative, and financial vocabularies.
* **Dynamic Domain Specialization (`--field`)**: Rapid contextual adaptation (e.g., Financial, Administrative, Legal, PowerShell).
* **Cross-Lingual Adaptation (`--lang`)**: Seamless translation without losing structured control-flow logic.
* **Automated Audit Pipeline**: Integrated premise verification and zero-base pruning to eliminate over-engineering.

---

## 🛠 Directory Structure

```text
skill-optimize/
├── skills/                      # Agent skill definitions
│   ├── skill-optimize-bpk/
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

## 💻 CLI & Usage

### Basic Optimization
```bash
python -m skill_optimize --input skills/my-skill/SKILL.md --output skills/my-skill/SKILL.md
```

### Domain & Language Adaptation
```bash
# Optimize for Legal domain in English
python -m skill_optimize --input input.md --field "Legal, Consent" --lang "English"

# Optimize for Financial asset management
python -m skill_optimize --input input.md --field "Finance, Portfolio" --lang "Japanese"
```

### Options
| Parameter | Type | Description |
| :--- | :--- | :--- |
| `--field`, `-f` | String | Target domain/specialization field |
| `--lang`, `-l` | String | Target output language |
| `--lite` | Flag | Enforce 1-Tier Lite mode for short utilities (<100 lines) |
| `--rename`, `-r` | String | Specify output skill identifier |

---

## 🛡 Design Principles & Anti-Patterns

* ❌ **No Over-Specification**: Utility skills (<100 lines) automatically fallback to 1-Tier Lite.
* ❌ **No Meta-Tag Leakage**: `[Tier 1]` / `[Tier 2]` tags are stripped from operational prompts.
* ❌ **Zero Domain-Term Loss**: Legal clauses and administrative terms are preserved verbatim.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
