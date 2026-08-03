# 🚀 Marketing Skills for AI Agents

> **A modular Markdown-based skill library for AI coding agents (Claude Code, Cursor, OpenClaw, Windsurf, Lovable).**  
> Turn your AI assistant into a specialized growth marketer, SEO strategist, conversion copywriter, and brand director without context bloat.

---

## 📌 Overview

**`Marketing-Skills-TT`** is an open-source library of structured AI Agent Skills (`SKILL.md` workflows). 

While AI agents are great at writing code, they often generate generic or fluff-filled marketing advice. This repository solves that by giving your agent concrete frameworks, mental models, decision trees, and best-practice checklists for full-funnel growth engineering.

### Why Modular Skills?
Instead of stuffing massive prompts into your agent's system instructions, this library is broken into **atomic, task-specific skills**. Your AI agent automatically reads only the skill file relevant to your prompt (e.g., loading `/landing-page` or `/seo-audit`), keeping your context window lightweight and output precision high.

---

## 📂 Repository Structure

```micro
Marketing-Skills-TT/
├── project-context.md          # 🔑 Global Brand & Product Context (Fill this out first!)
└── skills/
    ├── strategies/             # High-level positioning, brand identity, & go-to-market
    │   ├── branding/           # Brand purpose, voice, archetypes & narrative
    │   ├── content-strategy/    # Content pillars & hub-and-spoke models
    │   └── marketing-ideas/    # Growth experiments & acquisition channels
    ├── pages/                  # High-converting page UX, copy, & layout specs
    │   ├── homepage/           # Hero sections, navigation, & orientation
    │   ├── landing-page/       # Single-conversion offer pages
    │   ├── pricing-page/       # Tier matrices & feature comparisons
    │   └── about-page/         # Founder stories & trust building
    ├── channels/               # Channel-specific execution workflows
    │   ├── seo/                # Keyword research, schema, title tags, meta descriptions
    │   ├── social/             # LinkedIn posts, TikTok scripts, Twitter/X threads
    │   └── email/              # Cold outreach, lifecycle drips, onboarding flows
    └── cro/                    # Conversion Rate Optimization
        ├── page-cro/           # On-page teardowns & heuristic evaluations
        └── ab-testing/         # Experimentation design & hypothesis frameworks
