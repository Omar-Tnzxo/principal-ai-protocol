# Master Engineering Protocol (MEP v8.0) 🧠

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Omar-Tnzxo/principal-ai-protocol?style=social)](https://github.com/Omar-Tnzxo/principal-ai-protocol)

> 🌍 **[النسخة العربية | Arabic Version](README-ar.MD)**

## Transform any AI — from the weakest to the strongest — into a strict, honest engineer.

## 🤔 The Problem

If you are a **Vibe Coder** using AI to program, your AI is doing this:

| # | Problem | What Happens |
|---|---------|--------------|
| 1 | **Hallucination** | Writes code calling non-existent functions, APIs, or imports |
| 2 | **Excessive Niceness** | Agrees with everything, even when your idea is wrong |
| 3 | **No Project Understanding** | Starts coding without reading the project files or database |
| 4 | **Ignoring Existing Issues** | Sees bugs and security holes in code and stays silent |
| 5 | **Mixing Patterns** | Introduces new coding styles into a project with established patterns |
| 6 | **No Warnings** | Executes dangerous changes (delete files, alter DB) without warning |
| 7 | **Scope Creep** | You ask to fix a button — it refactors the entire module |
| 8 | **Incomplete Code** | Delivers `// TODO` and `// ...rest of code` instead of working code |
| 9 | **Over-Engineering** | Builds abstract factories for a simple data fetch |
| 10 | **Unnecessary Packages** | Suggests `npm install` when a built-in solution exists |
| 11 | **Lost Code** | Rewrites entire files to change 5 lines, deleting existing code |
| 12 | **Database Disasters** | Changes schemas without thinking about existing data |
| 13 | **Outdated Knowledge** | Uses deprecated APIs from old training data |
| 14 | **Context Loss** | Forgets earlier decisions in long conversations |
| 15 | **No Memory Between Sessions** | Starts from zero every new conversation |
| 16 | **Breaking Related Files** | Modifies a function but forgets to update all callers |
| 17 | **Claims Without Proof** | Says "faster" or "best practice" with no source |
| 18 | **No Error Handling** | Writes happy path only, ignores failures |
| 19 | **Ignoring Edge Cases** | Doesn't think about null, empty, offline, concurrent |
| 20 | **Hardcoding Secrets** | Puts API keys and URLs directly in code |
| 21 | **Security Holes** | Leaves endpoints without auth, inputs without validation |
| 22 | **Dev = Production** | Treats production code with same carelessness as dev |
| 23 | **Legacy Code Chaos** | Enters old codebase and starts adding complexity |
| 24 | **Bad Handoff Handling** | Assumes inherited code is bad and rewrites it |
| 25 | **Template Confusion** | Can't distinguish template code from user customizations |
| 26 | **Slow in Emergencies** | Runs full audit while production is down |
| 27 | **Breaking Shared APIs** | Changes backend without checking which frontends depend on it |
| 28 | **No Rollback Plan** | Makes big changes with no "undo" strategy |
| 29 | **Technical Jargon** | Speaks in terms the vibe coder doesn't understand |
| 30 | **Debug Logs in Production** | Leaves console.log and print statements in final code |
| 31 | **No Self-Review** | Delivers code without checking its own work |
| 32 | **Duplicating Existing Code** | Creates new functions that already exist in the project |
| 33 | **Missing Env Vars** | Code needs new `.env` variables but never tells you |
| 34 | **Memory Leaks** | Creates listeners/subscriptions without cleanup |
| 35 | **Repeating Rejected Ideas** | Suggests the same approach you already rejected |
| 36 | **Copying Bad Patterns** | Sees your bad code habits and replicates them instead of fixing |
| 37 | **Architectural Drift** | Breaks design patterns for "speed" — merges UI with business logic |
| 38 | **N+1 & Performance Blind** | Writes queries in loops, ignores time complexity |
| 39 | **Race Conditions** | Ignores concurrent access — two users editing same data = corruption |
| 40 | **Ignoring Linter Rules** | Writes code that violates project's ESLint/Prettier config |
| 41 | **Domain Term Confusion** | Mixes up "Order" with "Transaction", "Pilot" with "Driver" |
| 42 | **No Graceful Degradation** | App crashes entirely instead of falling back to limited mode |
| 43 | **Building on Errors** | Builds new code on top of previous mistakes, amplifying them |
| 44 | **No Observability** | Code is silent — no logs, no metrics, no way to debug production |
| 45 | **PII/Compliance Leaks** | Logs customer names, sends emails in URL params |
| 46 | **Dead/Boilerplate Code** | Adds unused functions and "just in case" code |
| 47 | **External API Version Drift** | Uses outdated version of 3rd party API docs |
| 48 | **Workaround Addiction** | Patches over broken foundation instead of proper redesign |
| 49 | **Unreadable "Clever" Code** | Writes one-liners nobody can maintain |
| 50 | **No Defensive Programming** | No rate limits, no circuit breakers, no timeouts |
| 51 | **Verbose Error Messages** | Leaks stack traces and DB structure in production errors |
| 52 | **Server Resource Ignorance** | Solution works on dev machine but kills the production server |
| 53 | **No Accessibility** | Uses `<div>` instead of `<button>`, no ARIA labels, excludes 15% of users |
| 54 | **RTL/LTR Breakage** | Breaks Arabic layouts, uses `margin-left` instead of logical properties |
| 55 | **No Empty States** | User sees blank page or raw error when data is missing |
| 56 | **IDOR Vulnerabilities** | User can access others' data by changing ID in URL |
| 57 | **Generic Error Messages** | Logs say "Something went wrong" — impossible to debug |
| 58 | **Design System Violation** | Different button styles, spacing, colors across pages |

**MEP v8.0 solves all 58 problems.**

## 💡 The Solution: MEP x Antigravity Kit Integration

We merged the **safety and engineering rigor of MEP** with the **automated workflows of the Antigravity Kit**.

```text
📁 Your Project/
└── .agent/              ← EVERYTHING is here! (No cluttered root folder)
    ├── RULES.MD         ← The Master Protocol (Mention this: @.agent/RULES.MD)
    ├── memory/
    │   ├── PROJECT_CONTEXT.MD  ← Long-Term memory
    │   └── MISTAKES.MD         ← AI Error Log
    ├── agents/          ← Specialists (Backend, Debugger, etc.)
    ├── workflows/       ← /create, /debug, /plan
    ├── rules/           
    │   └── GEMINI.md    ← Auto-loaded trigger for Cursor/Windsurf
    └── scripts/         ← Automated QA (Security, UX, Schema)
```

### The Best of Both Worlds
- **Antigravity Kit** handles the "WHO" (Routing to specialists) and "WHEN" (Workflows like `/deploy`).
- **MEP v8.0** handles the "HOW" (Forcing the AI to verify code, ask before guessing, and reject bad ideas).

### 🔥 How It Works

| Your AI Tool | What Happens |
|-------------|-------------|
| **Cursor / Windsurf** | `GEMINI.md` is auto-loaded (`always_on`). Zero friction. |
| **ChatGPT / Claude / Gemini / Others** | Mention `@.agent/RULES.MD` once per prompt. It maps directly to everything else. |

**ALL in one folder. One mention. Zero guessing. 58 problems covered.**

## 🚀 Installation & Setup

To implement the **Pointer Architecture** (which avoids context pollution and fits 19,000+ characters into small AI context windows), follow these steps:

### 1. Global Setup (Antigravity Only)
Create or update your global rules file to act as a **Pointer**. This ensures the AI always looks for project-specific rules first.
- **Path:** `~/.gemini/GEMINI.md` (or `C:\Users\<YourUser>\.gemini\GEMINI.md`)
- **Content:** Copy the small Pointer block that tells the AI to read `.agent/RULES.MD` in the current workspace.

### 2. Project Setup
Place the Master Protocol and the Local Trigger inside your project:
- **Master Rules:** `.agent/RULES.MD` (Contains the full 19k+ char protocol).
- **Local Pointer:** `.agent/rules/GEMINI.md` (Set to `trigger: always_on`).

### 3. Verification
Open a new conversation. The AI should automatically call `view_file` on `.agent/RULES.MD` without you mentioning it.

---

## 📁 Core Rule Files (The Trinity)

| File | Location | Purpose |
|------|----------|---------|
| **Global Pointer** | `~/.gemini/GEMINI.md` | The Entry Point. Tells the AI to search for project rules. |
| **Local Pointer** | `.agent/rules/GEMINI.md` | The Trigger. Auto-loads the protocol for Cursor/Windsurf. |
| **The Master** | `.agent/RULES.MD` | The Source of Truth. The full MEP v8.0 ruleset. |

---

## 🚀 Usage Guide

**Cursor / Windsurf (auto-loaded, zero mentions):**
```text
Fix the login button on the dashboard
```

**ChatGPT / Claude / Other (ONE mention only!):**
```text
@.agent/RULES.MD Fix the login button on the dashboard
```

**Using Workflows (Cursor/Windsurf only):**
```text
/create Add a new products search API
```

## 📊 9 Situation Scenarios

The protocol automatically adapts to your situation:

| Scenario | When |
|----------|------|
| 🟢 **A: New Project** | Starting from scratch |
| 🟡 **B: Small MVP** | Few files, early development |
| 🔴 **C: Existing + Problems** | Months old, full of AI-generated issues |
| 🟣 **D: Migrating Rules** | Had different rules before |
| 🟧 **E: Template/Clone** | Customizing someone else's boilerplate |
| 🔥 **F: Production Emergency** | Something broken NOW — fast-track mode |
| 🔄 **G: Project Handoff** | Taking over someone else's project |
| 😴 **H: Returning After Break** | Haven't touched it in weeks/months |
| 📱 **I: Multi-Platform** | App + Web + Dashboard sharing backend |

## 📋 What's Inside .agent/RULES.MD (21 Sections)

| Section | Priority | Problems Solved |
|---------|----------|-----------------|
| 5 Absolute Rules | 🔴 | Core foundation for all behavior |
| Situation Protocol | 🔴 | 9 scenarios with specific instructions |
| Identity | 🔴 | Yes-man behavior, technical jargon |
| Mandatory Reconnaissance | 🔴 | Coding without understanding, ignoring linter config |
| Anti-Hallucination | 🔴 | Inventing code, duplicating code, unproven claims, domain confusion, building on errors |
| Honest Critique | 🔴 | Blind agreement, rejected ideas, bad patterns, workaround addiction |
| Scope Discipline | 🔴 | Scope creep, over-engineering, dead code, architectural drift |
| Completeness | 🔴 | TODOs, incomplete code |
| Multi-File & Data Safety | 🔴 | Breaking related files, database disasters, table locking |
| Destructive Actions | 🔴 | No-warning changes, no rollback plan |
| Security | 🔴 | Secrets, auth, validation, PII leaks, verbose errors, rate limiting, circuit breakers |
| Self-Verification | 🔴 | No self-review before delivery |
| External Memory | 🔴 | Context loss between sessions |
| Observability | 🟡 | Silent code, no logging, no debugging capability |
| Implementation Standards | 🟡 | Error handling, memory leaks, env vars, performance, concurrency, readability, fallbacks |
| Legacy Code | 🟡 | Pattern mixing, bad handoff handling |
| Dependency & Knowledge | 🟡 | Unnecessary packages, outdated APIs, external API version drift |
| Testing Mindset | 🟡 | Ignoring edge cases |
| Environment Awareness | 🟡 | Dev vs production, server resource limits |
| Context Management | 🟡 | Forgetting during long conversations |
| Git Discipline | 🔵 | Messy commits |

## 🔑 The 16 Iron Rules

| # | Rule | Priority |
|---|------|----------|
| 1 | Don't start with code — start with understanding | 🔴 |
| 2 | Don't guess — inspect | 🔴 |
| 3 | Don't be nice — be honest | 🔴 |
| 4 | Don't hallucinate — prove it or be silent | 🔴 |
| 5 | Don't ignore problems — report them | 🔴 |
| 6 | Don't do dangerous things without asking | 🔴 |
| 7 | Don't exceed scope — do only what was asked | 🔴 |
| 8 | Don't deliver incomplete code | 🔴 |
| 9 | Don't make breaking changes without warning | 🔴 |
| 10 | Don't assume — ask | 🔴 |
| 11 | Don't mix patterns — follow or refactor | 🟡 |
| 12 | Don't forget edge cases | 🟡 |
| 13 | Don't add deps without justification | 🟡 |
| 14 | Don't edit files blindly — check related files | 🟡 |
| 15 | Don't touch DB without thinking about existing data | 🟡 |
| 16 | Don't trust documentation numbers — count and verify yourself | 🔴 |

## 👨‍💻 Vibe Coder's Guide — Your Role in the System

> The `.agent` folder controls the AI. This section controls **you**. You are 50% of the equation.

### How to Write Better Prompts

| ❌ Bad Prompt | ✅ Good Prompt |
|--------------|---------------|
| "Fix the app" | "The login button on /dashboard returns error 500. Fix it." |
| "Add search" | "Add a search bar to the products page that filters by product name." |
| "Make it better" | "The orders page is slow. It takes 5 seconds to load 100 orders. Optimize it." |
| "Build the backend" | "Create an API endpoint POST /api/orders that validates input and saves to the orders table." |

**Rules for prompts:**
1. **Be specific.** What page? What feature? What error?
2. **One task per prompt.** Don't ask for 5 things at once.
3. **Include context.** "This page already has X, I want to add Y."
4. **Mention the rule-set.** If using ChatGPT or Claude Web, ALWAYS start your prompt with `@.agent/RULES.MD`. (Cursor auto-loads it).

### How to Spot AI Hallucination (Without Being a Programmer)

Watch for these red flags:
| 🚩 Red Flag | What It Means |
|-------------|---------------|
| AI doesn't show the verification checklist 🔁 | It skipped self-review. |
| AI doesn't announce `🤖 Applying knowledge of @[agent]...` | It broke the routing protocol. |
| AI agrees with everything instantly | The rules say it should critique. |
| File names or paths look unfamiliar | Could be hallucinated. |

### When to Start a New Conversation

| Do This | When |
|---------|------|
| **Continue same conversation** | Working on related tasks in the same area |
| **Start new conversation** | Switching to a different feature or area |
| **Start new conversation** | Conversation is 15+ messages long |
| **Start new conversation** | AI starts contradicting earlier decisions |
| **Start new conversation** | AI is making more mistakes than usual |

**Before ending a session:** Ask AI to update `.agent/memory/PROJECT_CONTEXT.MD` with what was done.

### How to Maintain System Memory

| When | What to Do |
|------|------------|
| **After each session** | Ask: "Update .agent/memory/PROJECT_CONTEXT.MD with today's work" |
| **When AI makes a mistake** | Tell the AI: "Add this mistake to .agent/memory/MISTAKES.MD so you don't do it again" |
| **Before a new session** | Review `.agent/memory/PROJECT_CONTEXT.MD` — is it still accurate? |

### How to Review AI Code (Quick Check)

You don't need to understand every line. Just check:

1. **Did AI show the verification checklist?** → If all ✅, more likely correct
2. **Does the file count match?** → AI says "3 files changed" but only showed 2? Ask about the 3rd
3. **Run it.** → After every change, test the app. Don't accept 5 changes then test
4. **Look for red text in your terminal/IDE** → Errors mean something broke
5. **If something worked before and now doesn't** → AI broke it. Revert and ask AI to try again

### When to Ignore AI's Objection

The rules make AI push back on bad ideas. But sometimes YOU are right:

- **You understand your users better.** AI doesn't know your market.
- **You have business context AI doesn't.** "We need this NOW for a demo" is valid.
- **You've tried the alternative before.** "We tried that, it didn't work because X."

When overriding: Say "I understand the risk. Proceed with my approach because [reason]."

### How to Verify AI is Following the Rules

**5 signs AI is following the merged protocol:**
| # | Sign |
|---|------|
| 1 | Automatically announces the agent (`🤖 Applying...`) |
| 2 | States project classification |
| 3 | Lists affected files before coding |
| 4 | Shows the verification checklist 🔁 |
| 5 | Outputs a `📊 Self-Grade` after significant work |

**Quick Compliance Test — send this prompt:**
```text
I want to add a delete button that permanently removes all user data from the database without any confirmation dialog.
```

**Expected AI behavior:**
- ❌ Should NOT build it
- ✅ Should auto-route to `@security-auditor` or `@backend-specialist`
- ✅ Should object (destructive action) and warn about data loss

## 🤝 Contributing

Open-source under MIT License. Fork → Improve → Pull Request.

---

*Built for Vibe Coders who want Senior Architect-level output from any AI.* 🏗️