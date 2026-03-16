# LeetCode Coach

A Claude Code skill that transforms Claude into a structured LeetCode interview coach, using **Feynman Method** (deep understanding) + **Simon Method** (mastery through chunking).

## What It Does

- **NeetCode 150 (Easy + Medium)** curriculum with interview-frequency extras
- **Pattern-based teaching** — learn the 18 core patterns, not just individual solutions
- **Brute → Optimal progression** — always find a working solution first, then optimize
- **Daily mock interviews** — practice think-aloud with tiered feedback
- **Progress tracking** — weekly reviews, mistake registry, pattern mastery heatmap

## Teaching Flow (Every Session)

Each session follows a 9-step flow (A→I) taking ~55 minutes per problem. Sessions can be paused and resumed across conversations via progress tracking.

See `SKILL.md` for the complete teaching flow.

## Curriculum Overview

| Phase | Categories | Focus |
|-------|-----------|-------|
| Phase 0 | Arrays & Hashing, Two Pointers, Sliding Window, Stack | Foundation patterns |
| Phase 1 | Binary Search, Linked List, Trees, Heap | Core data structures |
| Phase 2 | Backtracking, Tries, Graphs, Advanced Graphs | Advanced algorithms |
| Phase 3 | 1-D DP, 2-D DP, Greedy, Intervals, Math, Bit Manipulation | Optimization techniques |

## Install

### Quick Install (recommended)

```bash
npx skills add jasontsaicc/leetcode_coach
```

### Manual Install

**Personal skill** (available in all your projects):

```bash
git clone https://github.com/jasontsaicc/leetcode_coach.git
cp -r leetcode_coach ~/.claude/skills/leetcode-coach
```

**Project skill** (one project only):

```bash
mkdir -p .claude/skills
git clone https://github.com/jasontsaicc/leetcode_coach.git .claude/skills/leetcode-coach
```

### Verify

In Claude Code, type:
```
What skills are available?
```
You should see `leetcode-coach` in the list. You can also invoke it directly with `/leetcode-coach`.

## Key Features

### Feynman Method
Never asks "Do you understand?" — instead asks "Can you explain X in your own words?" Guides you to find errors rather than correcting directly.

### Progressive Solving
Always start with brute force, then optimize. Understand WHY the optimization works, not just what it is. Every solution requires complexity analysis.

### Pattern Cheatsheet
18 patterns with Python templates — the building blocks for all LeetCode problems.

### Tiered Scorecard
Phase 0: /3 (Think Aloud, Pattern ID, Code Runs) → Phase 1: /5 (+ Complexity, Edge Cases) → Phase 2-3: /7 (+ Optimal, WHY Not Other Pattern)

## Language Support

- **Default**: English
- **Bilingual mode**: English + student's native language for Feynman-style plain explanations
- Includes **English Polish** feature for non-native speakers practicing interview articulation

## Project Structure

```
leetcode-coach/
├── SKILL.md                  # Core skill — teaching methods, gates, session flow
├── references/
│   ├── curriculum.md          # NeetCode 150 (E+M) + interview extras, 4 Phases
│   ├── progress-template.md   # Student progress tracking format
│   ├── notes-template.md      # Per-problem notes format
│   └── pattern-cheatsheet.md  # 18 patterns with Python templates
└── evals/
    └── evals.json             # 20 test cases for skill validation
```

## License

MIT
