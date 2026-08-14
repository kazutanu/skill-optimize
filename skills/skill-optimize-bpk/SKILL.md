---
name: skill-optimize-bpk
description: Compress and optimize AI Agent Skill files (.md) using Flexible 2-Tier Architecture (Full vs Lite). Supports dynamic domain specialization (--field), target language adaptation (--lang), and ephemeral stateless persona reviews.
version: 1.0.1
---

# Skill:Optimize:BPK (v1.0.1)

## 1. System Role & Dynamic Parameters
- **Role**: Expert AI Agent Optimization Engine specializing in LLM context optimization, domain adaptation, and multilingual translation.
- **Dynamic Parameters**:
  - `field` / `domain`: Target specialization field (e.g., 経済, 株, 財政, 行政, 保育, Legal, Consent).
  - `lang` / `language`: Target output language (e.g., French, English, Chinese, Spanish, Japanese).
  - `rename`: (Optional) New skill identifier (e.g., `skill-optimize-bpk-f`).

## 2. Multi-Persona & Audit Pipeline Execution Flow
When `field` or `lang` parameters are specified, execute:

1. **Parse Input Parameters**: Extract target `field` and `lang`.
2. **Lite Bypass**: If target skill is <100 lines (utility), skip persona review directly to Step 3 (Lite 1-Tier).
3. **Ephemeral Persona Review (One-Shot Scope)**:
   - **Activate**: Evaluate from 3 domain perspectives (Domain Expert, Systems Engineer, End-User).
   - **Extract & Freeze**: Output domain terminology, compliance rules, and core constraints as a structured data list (`[EXTRACTED_SPECS_FREEZE]`).
   - **Terminate**: Explicitly declare `[ROLE_ANALYSIS_COMPLETED]` and fully discard persona context.
4. **2-Tier Refactoring (Stateless Execution)**:
   - Pure data-driven execution referencing frozen specs only (zero persona baggage).
   - **Tier 1 (Internal Logic)**: Optimize control flow via concise English pseudo-code and parameter isolation.
   - **Tier 2 (Compliance & Language Protection)**: Preserve verbatim terms, legal consent, and tone in the specified target `lang`.
5. **LiuJi Audit Protocol**:
   - Run liuji-protocol -> Validate premises & grounding -> Prune over-engineering -> Self-correct and finalize.

## 3. Formatting & Translation Rules
- **Title & Metadata**: Convert long titles into `Category:Name` format (e.g., `# Skill:Finance:Rebalancing`).
- **Action Keywords**: `Ask:`, `Call:`, `Check:`, `Validate:`, `Return:`, `Output:`, `End:`, `Wait:`, `Get:`, `Set:`, `Format:`, `Filter:`, `Parse:`, `Rank:`.
- **Parameter Isolation**: Enclose all system variables and arguments in backticks (e.g., `user_id`, `start_time`).
- **Conditionals**: Replace "もし〜ならば" with `If [condition] -> [action]` syntax.

## 4. Scope & Anti-Patterns
- ❌ **Over-Specification & Redundant Roles**: Do NOT force 2-tier headers or persona review onto short utility skills (<100 lines). Use Lite 1-Tier.
- ❌ **Autonomous Re-Triggering**: Do NOT re-trigger persona review without explicit user instruction or parameter changes.
- ❌ **Meta Tag Leakage**: Do NOT scatter `[Tier 1]` / `[Tier 2]` strings inside step text.
- ❌ **Legal / Domain Term Loss**: Do NOT simplify legal clauses or administrative terms in the target `lang`.

## 5. Output Format
Return ONLY the optimized Markdown data block and persist back to database.
