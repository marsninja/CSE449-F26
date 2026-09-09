# Assignment 1: Personal Planning App in Jac

**Points**: 1% participation grade, plus up to 3% extra credit for an impressive project
**Due**: Monday, October 5, 2026 (Week 6)
**Format**: Individual project
**Submission**: GitHub repository link submitted via Canvas

---

## Overview

Build yourself a **personal planning tool using Jac**: an application that helps you organize your own life, coursework, tasks, goals, or schedule. Design something you would actually want to use.

Your project must include a **server component, a web frontend, a mobile app, and a command-line interface (CLI)**. These should work together as parts of the same planning tool, sharing planning data and functionality where appropriate.

This may sound ambitious, but Jac makes it realizable. You have a complete example workspace to learn from, along with documentation and a step-by-step day-planner guide. Use these resources to understand how the pieces fit together, then make the planner your own.

---

## What to Build

Your application must include all four components:

1. **Server** — Implement the planning logic and persist planning data so it remains available between sessions.
2. **Web frontend** — Provide a usable browser interface for managing your plans.
3. **Mobile app** — Provide a mobile interface for useful planning actions, connected to the same backend.
4. **CLI** — Make useful planning actions available from the terminal, such as adding a task, viewing today's plan, or marking an item complete.

Build these components using Jac. The interfaces can focus on different workflows, but each must provide working functionality. For example, you might plan your week on the web, check and complete tasks on your phone, and quickly add tasks from the terminal.

Choose the planning features that fit your needs. Possible directions include:

- Coursework, assignment deadlines, and study sessions
- Daily or weekly schedules with priorities and time blocks
- Goals, habits, and progress tracking
- Recurring tasks and reminders
- AI-assisted task breakdowns or schedule suggestions

These are ideas, not a required feature checklist. The goal is a coherent, useful personal planning tool.

---

## Getting Started and Learning Resources

### Explore the Complete Example

Get the full source for the `jaclang_org` example workspace locally by running:

```bash
jac create --awesome
```

This is the example from `jac/examples/jaclang_org/` in the Jac source repository. It demonstrates a complete application with server functionality, a web frontend, a mobile app, and a CLI sharing a common core. Explore its `jac.toml`, `core/`, `web/`, `mobile/`, and `cli/` to see how the project is organized and how its components work together.

Draw inspiration from this solution and adapt the patterns to your personal planner. Your submission should demonstrate your own planning workflows and design choices.

### Use the Documentation and Day-Planner Guide

You are encouraged to use:

- [Jac documentation](https://jaclang.org/docs/latest) — Learn the language and look up the features you need as you build.
- [Build an AI Day Planner](https://jaclang.org/docs/v0.37/tutorials/first-app/build-ai-day-planner) — Use this guide as a starting point for learning how to build your planner.

Start with a working planning workflow, then extend it across the web, mobile app, and CLI. Use the full example alongside the guide to learn how to connect all four components.

---

## Grading

- **Participation: 1%** for completing and submitting a working individual project that meets the requirements above, with clear instructions for running it.
- **Extra credit: up to an additional 3%** based on how impressive your project is. We will consider usefulness, creativity, depth of functionality, polish, reliability, and how well the server, web, mobile, and CLI components work together.

A thoughtful, polished tool that solves your planning needs can be more impressive than a long list of unfinished features. Make it easy for us to see what makes your project stand out.

---

## Submission Requirements

Submit a **link to your GitHub repository on Canvas**. Include all source code and a root-level `README.md` with:

- Your name and UMID
- A brief description of your planner and its main features
- Instructions for setting up and running the project, including any prerequisites or configuration
- Instructions for launching and using the mobile app and CLI
- A short explanation of how the four components fit together and what makes your project impressive

Once the repository is checked out and any documented prerequisites are ready, starting the web application and its server should be as simple as running this from the repository root:

```bash
jac run
```

Configure the default app accordingly. Document any separate commands or platform setup needed for mobile and CLI use.

Before submitting, try your README instructions from a fresh checkout and verify that the web, mobile, and CLI workflows work with your server.
