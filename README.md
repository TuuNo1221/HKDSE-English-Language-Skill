# HKDSE-English-Language-Skill

An [Agent Skill](https://agentskills.io/specification) for Hong Kong Diploma of Secondary Education (HKDSE) English Language practice.

| Paper | Skill support |
| --- | --- |
| 1 Reading | Passage analysis, question strategies, worked answers |
| 2 Writing | Guided and extended compositions, genre guidance, and draft feedback |
| 3 Listening and Integrated Skills | Listening strategies and integrated writing from a data file and listening input |
| 4 Speaking | Group interaction, individual responses, and mock practice |

## Install and use

Clone the repository. Copy the `hkdse-english-language-skill` directory into your harness's skill directory. In Codex, place it under `.agents/skills/` in your project. Use the skill by name or ask for HKDSE English help. [Codex skills documentation](https://developers.openai.com/codex/skills)

```sh
git clone https://github.com/TuuNoGITHUB/HKDSE-English-Language-Skill.git
```

Try these prompts.

- “Use hkdse-english-language-skill to solve these Paper 1 questions and explain the clues for each answer.”
- “Use hkdse-english-language-skill to plan this Part A advice email. Map both bullet points before suggesting an opening.”
- “Review my Part B speech for content, language, and organisation. Show the three edits I should make first.”
- “For this Paper 3 task, map the email requirements to my data file and listening notes, then draft the email.”
- “Run a Paper 4 group discussion mock. Play two other candidates and wait for my reply each turn.”

## Detailed references

- [Paper 1 reading](hkdse-english-language-skill/references/reading.md), [Paper 2 genres](hkdse-english-language-skill/references/genres.md), [Paper 3 listening and integrated writing](hkdse-english-language-skill/references/integrated-writing.md), and [Paper 4 speaking](hkdse-english-language-skill/references/speaking.md).
- [Sentence patterns B1–B32 and A1–A33](hkdse-english-language-skill/references/sentence-patterns.md), [grammar and revision](hkdse-english-language-skill/references/language.md), [word study](hkdse-english-language-skill/references/word-study.md), and [writing craft](hkdse-english-language-skill/references/writing-craft.md).
- The [source index](hkdse-english-language-skill/references/source-index.md) maps all 40 handouts to the relevant guidance. To use exact original exercises, extract your own PDFs into `source-notes/` inside the skill folder. A local full-notes package can use that same layout. The public repository contains the skill, source index, and original teaching examples.

## Sources

The skill is based on the complete `ENG notes.zip` classroom archive. It adapts notes on passage decoding and comprehension, writing formats, advice and persuasion, sentence patterns, integrated writing, and speaking. The repository contains rewritten guidance and original examples. Exam-format details use the [HKEAA 2027 English Language Assessment Framework](https://www.hkeaa.edu.hk/DocLibrary/HKDSE/Subject_Information/eng_lang/2027hkdse-e-elang.pdf). Use the instructions on the paper you are practising with.
