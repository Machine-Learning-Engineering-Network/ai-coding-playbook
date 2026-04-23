
# Codex Guide

A practical guide to using Codex-style AI tools for real development workflows.

---

## What Codex actually does

Codex is best used for **building and modifying systems**, not just answering questions.

Use it for:

- generating project structure  
- building features  
- refactoring code  
- debugging workflows  

> Treat Codex like a developer, not a chatbot.

---

## Core workflow

1. Define the system  
2. Give constraints  
3. Let Codex implement  
4. Review output  
5. Iterate  

> Build → Review → Refine

---

## Prompting properly

Bad:

> build a dashboard  

Better:

> Build a modular dashboard using React and Tailwind. Keep components reusable and structured.

---

## Structured prompting

Always include:

- Goal → what you want  
- Context → project details  
- Constraints → rules to follow  

### Template

Goal:

[what to build]

Context:

[project info]

Constraints:

[rules]

---

## Using context files

Context files improve consistency and accuracy across your project.

---

### AGENTS.md

Defines how the AI should behave:

```md
You are a senior developer.

Keep code modular and production-ready.

Do not rewrite unrelated files.

Prefer readable and scalable solutions.
```

### SKILLS.md

Defines your stack and focus:

```React
Node.js
MongoDB
REST APIs

Focus on:
- clean architecture
- reusable components
- scalable structure
```

### Advanced usage

> System-level thinking

Codex performs best when:

* working step-by-step
* building features incrementally
* following a defined structure

Avoid asking for entire applications in one prompt.

---

> Use constraints to control output

Examples:

* “Do not modify existing authentication logic”
* “Keep the current folder structure”
* “Only update the affected files”

---

## Iterative workflow

Instead of one large prompt:

1. Build base system
2. Add feature
3. Refactor
4. Optimize

This leads to better results and fewer errors.

---

## Limitations

* May over-generate code
* Can break structure without constraints
* Requires testing and review

---

## Good habits

* Be specific
* Build one feature at a time
* Preserve working code
* Always test results
* Ask for summaries after changes

---

## Common mistakes

* Being too vague
* Asking for too much at once
* Not providing context
* Letting it rewrite entire systems
* Not verifying output

---

## Final tip

Codex is strongest when you guide it with clear direction and structure.

Use it to build systems, not just generate code.
