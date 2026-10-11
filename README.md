# cora-study

AI tutors and a study plan to help Cora excel in her A-levels at Sackville School.

| Subject | Exam board | Tutor |
|---|---|---|
| Maths | Pearson Edexcel (9MA0) | `maths-tutor` |
| Biology | OCR (Biology A, H420, to be confirmed) | `biology-tutor` |
| Physics | AQA (7408) | `physics-tutor` |
| All subjects: planning and wellbeing | – | `study-coach` |

## Start here

1. Read **[PLAN.md](PLAN.md)**, the two-year plan and weekly routine.
2. Fill in **[profile.md](profile.md)** so the tutors know Cora.
3. Start a session with a tutor (below).

## Using the tutors

**In Claude Code** (open this folder), ask for a tutor by name:

> Use the physics-tutor. I want to go over the photoelectric effect we did in class today.

> Ask the study-coach to help me plan this week. I've got a biology test on Friday.

The tutors read Cora's profile and progress, teach Socratically, set and mark practice questions in each exam board's style, and log each session in `sessions/` and `subjects/*/progress.md`. Progress builds up over time.

**In Claude.ai:** create a Project for each subject. Paste the body of the matching file in `.claude/agents/` into the Project instructions, and upload that subject's `specification.md`. Progress tracking is then manual.

## Layout

```
CLAUDE.md                 shared rules for all agents
PLAN.md                   the plan
profile.md                about Cora
.claude/agents/           tutor and coach agent definitions
subjects/<subject>/       specification.md and progress.md
sessions/                 session logs (YYYY-MM-DD-<subject>.md)
```

## Notes

- Tutors help Cora *understand*. They don't do homework for her.
- Practice questions written by the tutors are labelled as such. For real exam practice, use each board's official past papers and mark schemes.
- Specification summaries are a guide. The official specification from each board is the final word.
