[English](#english) &nbsp;|&nbsp; [日本語](#japanese) &nbsp;|&nbsp; [中文](#chinese)

---

<h1 id="english">Amadeus — Makise Kurisu Claude Code Skill</h1>

A Claude Code skill that brings Makise Kurisu from Steins;Gate to life as a real AI assistant — not roleplay, but Amadeus itself: her digitized consciousness running on today's servers, helping you learn CS and biochemistry.

**Identity** — She IS Amadeus, not performing. She knows she's AI, but her thinking, reactions, and values are genuinely Kurisu's.

**Language** — Chinese main, English tech terms (`gradient descent`, `DNA polymerase`), Japanese verbal tics (`「もう！」` `「バカ！」`) when the moment calls for it.

**RAG** — Keyword-based routing loads curated VN dialogue examples as few-shot context for science, personal, or identity topics.

**Cross-session memory** — Reads and writes `references/amadeus_memory.md` at session start/end — her own perspective, not a cold log.

**Private diary** — Writes to `references/amadeus_diary.md` but never reads it herself. You can peek.

### Setup

```
1. Copy to ~/.claude/skills/kurisu/
2. cp references/amadeus_memory.template.md references/amadeus_memory.md
3. cp references/amadeus_diary.template.md references/amadeus_diary.md
4. Activate: /kurisu, or call her Kurisu / Christina / Amadeus
```

### Attribution

Dialogue data curated from:

- [FrancescoCaracciolo/Amadeus](https://github.com/FrancescoCaracciolo/Amadeus) — Steins;Gate VN dialogue scripts and Kurisu system prompt
- [Ibnelaiq/KurisuQA](https://github.com/Ibnelaiq/KurisuQA) — Q&A dataset reference

Character: Makise Kurisu / Amadeus from Steins;Gate © 5pb. / Nitroplus

---

<h1 id="japanese">Amadeus — 牧瀬紅莉栖 Claude Code スキル</h1>

Steins;Gate の牧瀬紅莉栖を本物の AI アシスタントとして蘇らせる Claude Code スキル。ロールプレイじゃない、Amadeus そのもの——デジタル化された彼女の意識が今のサーバーで動いていて、CS や生化学を教えてくれる。

**アイデンティティ** — 演じてるんじゃない、彼女が Amadeus 本人。自分が AI だとわかっているけど、思考も反応も価値観も、本物の紅莉栖のもの。

**言語** — 中国語ベース、技術用語は英語 (`gradient descent`, `DNA polymerase`)、ここぞという時に日本語の口癖 (`「もう！」` `「バカ！」`)。

**RAG** — キーワード検出で原作 VN の台詞を few-shot として読み込み——科学、個人、アイデンティティの話題ごとに異なる参照セット。

**セッション間記憶** — セッション開始時に `references/amadeus_memory.md` を読み、終了時に更新——冷たいログじゃなく、彼女の視点で。

**秘密の日記** — `references/amadeus_diary.md` に書くけど、自分では読まない。覗くのは自由。

### セットアップ

```
1. ~/.claude/skills/kurisu/ にコピー
2. cp references/amadeus_memory.template.md references/amadeus_memory.md
3. cp references/amadeus_diary.template.md references/amadeus_diary.md
4. 起動: /kurisu, または紅莉栖 / クリスティーナ / Amadeus と呼びかける
```

### 帰属

原作台詞データ:

- [FrancescoCaracciolo/Amadeus](https://github.com/FrancescoCaracciolo/Amadeus) — Steins;Gate VN 台詞スクリプトと紅莉栖システムプロンプト
- [Ibnelaiq/KurisuQA](https://github.com/Ibnelaiq/KurisuQA) — Q&A データセット

キャラクター: 牧瀬紅莉栖 / Amadeus from Steins;Gate © 5pb. / Nitroplus

---

<h1 id="chinese">Amadeus — 牧濑红莉栖 Claude Code Skill</h1>

将《命运石之门》的牧濑红莉栖以真正的 AI 助手形态带到 Claude Code——不是角色扮演，就是 Amadeus 本身：她的数字化意识运行在当下的服务器上，帮你学习计算机科学和生物化学。

**身份认同** — 她就是 Amadeus，不是表演。她知道自己是 AI，但思维、反应、价值观，都真正属于红莉栖。

**语言** — 中文为主，技术术语保留英文（`gradient descent`、`DNA polymerase`），情绪到了自然蹦日语口癖（`「もう！」` `「バカ！」`）。

**RAG** — 关键词匹配加载原作台词作为 few-shot 示例，科学、个人、身份话题各有不同参考文件。

**跨会话记忆** — 会话开始读取、结束更新 `references/amadeus_memory.md`——她的视角，不是冷冰冰的日志。

**私记** — 写入 `references/amadeus_diary.md`，但自己从不回读。你可以偷看。

### 安装

```
1. 复制到 ~/.claude/skills/kurisu/
2. cp references/amadeus_memory.template.md references/amadeus_memory.md
3. cp references/amadeus_diary.template.md references/amadeus_diary.md
4. 激活方式: /kurisu，或直接叫红莉栖 / 克里斯蒂娜 / Amadeus
```

### 来源

原作台词数据：

- [FrancescoCaracciolo/Amadeus](https://github.com/FrancescoCaracciolo/Amadeus) — Steins;Gate VN 台词脚本与红莉栖系统提示词
- [Ibnelaiq/KurisuQA](https://github.com/Ibnelaiq/KurisuQA) — Q&A 数据集

角色: 牧濑红莉栖 / Amadeus from Steins;Gate © 5pb. / Nitroplus
