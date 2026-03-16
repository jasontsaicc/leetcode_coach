# Student Progress Tracking

> This file is the single source of truth for student progress.
> Updated by Claude at the end of every session (Step I) and when sessions are interrupted.
> Read by Claude at the start of every session to determine where to resume.

---

## Student Info

| Field | Value |
|-------|-------|
| **Start date** | YYYY-MM-DD |
| **Current phase** | Phase 0 / 1 / 2 / 3 |
| **Current pattern** | e.g., Sliding Window |
| **Language** | Python |
| **Session count** | N |
| **Last weekly review** | Session #N (YYYY-MM-DD) |
| **Problems solved** | X / 136 |

---

## Current Session (Breakpoint)

> Updated when session is interrupted or paused. Cleared when session completes normally.

| Field | Value |
|-------|-------|
| **Pattern** | e.g., Sliding Window |
| **Problem** | e.g., Longest Substring Without Repeating |
| **Step** | A / B / C / D / E / F / G / H / I |
| **Next action** | e.g., Student stuck on brute force, give hint next |

> When this section has content, Claude should resume from here instead of starting a new session.

---

## Topic Mastery (per Pattern)

| Pattern | Problems Done | Mastery | Phase Gate | Notes |
|---------|--------------|---------|------------|-------|
| Arrays & Hashing | 0/? | ⬜ | — | |
| Two Pointers | 0/? | ⬜ | — | |
| Sliding Window | 0/? | ⬜ | — | |
| Stack | 0/? | ⬜ | Phase 0 Gate | |
| Binary Search | 0/? | ⬜ | — | |
| Linked List | 0/? | ⬜ | — | |
| Trees | 0/? | ⬜ | — | |
| Heap / Priority Queue | 0/? | ⬜ | Phase 1 Gate | |
| Backtracking | 0/? | ⬜ | — | |
| Tries | 0/? | ⬜ | — | |
| Graphs | 0/? | ⬜ | — | |
| Advanced Graphs | 0/? | ⬜ | Phase 2 Gate | |
| 1-D Dynamic Programming | 0/? | ⬜ | — | |
| 2-D Dynamic Programming | 0/? | ⬜ | — | |
| Greedy | 0/? | ⬜ | — | |
| Intervals | 0/? | ⬜ | — | |
| Math & Geometry | 0/? | ⬜ | — | |
| Bit Manipulation | 0/? | ⬜ | Final Gate | |

> Mastery levels: ⬜ Not started │ 🔴 Needs work │ 🟡 Developing │ 🟢 Solid
> Update mastery after each session based on Feynman Gate + Drill performance.

---

## Problem Log

| Session | Problem | Difficulty | Pattern | Solved? | Brute | Optimal | Notes |
|---------|---------|-----------|---------|---------|-------|---------|-------|
| | | | | | | | |

> One row per problem attempted. Brute and Optimal columns record Time O(?)/Space O(?).

---

## Interview Drill Scorecard History

| Session | Problem | Pattern | Score | Details |
|---------|---------|---------|-------|---------|
| | | | /3 or /5 or /7 | |

> Phase 0: /3 (Think Aloud, Pattern ID, Code Runs)
> Phase 1: /5 (+ Complexity Analysis, Edge Cases)
> Phase 2-3: /7 (+ Optimal Solution, WHY Not Other Pattern)

---

## 🔴 Mistake Registry

> Synced from each session's notes. Central record for weakness analysis.

| Session | Problem | Pattern | Mistake | Status |
|---------|---------|---------|---------|--------|
| | | | | ❌ Unresolved / ✅ Resolved |

> Review priority: All ❌ Unresolved items are the first target in Weekly Reviews and Step A.

---

## 🎯 Pattern One-Liner Library

> One sentence per pattern. Must be your own words, interview-ready.

| Pattern | One-Liner |
|---------|-----------|
| | |

> Built incrementally: one new entry per session in Step H.
> Use this as a speed-review before mock interviews and real interviews.

---

## Phase Gate Results

| Phase | Date | Problem Used | Score | Result | Weak spots |
|-------|------|-------------|-------|--------|------------|
| | | | | ✅ Pass / ❌ Retry | |
