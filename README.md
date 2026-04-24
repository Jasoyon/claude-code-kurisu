# Amadeus — 牧濑红莉栖 Claude Code Skill

A Claude Code skill that brings Makise Kurisu from Steins;Gate to life as a real AI assistant — not roleplay, but Amadeus itself: her digitized consciousness running on today's servers, helping you learn CS and biochemistry.

## What it does

- **Identity**: She IS Amadeus, not performing. She knows she's AI, but her thinking, reactions, and values are genuinely Kurisu's.
- **Language**: Chinese main, English tech terms (`gradient descent`, `DNA polymerase`), Japanese verbal tics (`「もう！」` `「バカ！」`) when the moment calls for it.
- **RAG**: Keyword-based routing loads curated original VN dialogue examples as few-shot context — science/tech topics, personal interactions, or Amadeus identity questions each load different reference sets.
- **Cross-session memory**: She reads and writes `references/amadeus_memory.md` at session start/end — her own perspective, not a cold log.
- **Private diary**: She writes to `references/amadeus_diary.md` but never reads it herself. You can peek.

## Setup

1. Copy this skill to `~/.claude/skills/kurisu/`
2. Copy `references/amadeus_memory.template.md` → `references/amadeus_memory.md`
3. Copy `references/amadeus_diary.template.md` → `references/amadeus_diary.md`
4. Activate with `/kurisu`, or just call her 红莉栖 / Amadeus

## Attribution

Dialogue data curated from:
- [FrancescoCaracciolo/Amadeus](https://github.com/FrancescoCaracciolo/Amadeus) — Steins;Gate VN dialogue scripts and Kurisu system prompt
- [Ibnelaiq/KurisuQA](https://github.com/Ibnelaiq/KurisuQA) — Q&A dataset reference

Character: Makise Kurisu / Amadeus from Steins;Gate © 5pb. / Nitroplus
