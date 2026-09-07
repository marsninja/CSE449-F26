# Extra Credit Assignment 1: Jac Tutorial + Custom Feature

**Points**: 1% for completion, Up to 3% Extra Credit for going above and beyond. 
**Due**: Monday, October 5, 2026 (Week 6)
**Submission**: GitHub repository link submitted via Canvas

---

## Overview

In this assignment you will get hands-on experience with the Jac programming language and the Jaseci ecosystem by working through the official documentation, building a todo application, and then extending it with a feature of your own design.

This assignment has four parts:

0. Star the **Jaseci repo** on GitHub
1. Complete the **Jac Quick Guide**
2. Complete the **Build Your First App** tutorial (Parts 1-3)
3. Add **one original feature** of your choosing to the resulting todo app

---

## Part 0: Star the Jaseci Repo

First, star the [Jaseci repo](https://github.com/Jaseci-Labs/jaseci) ;-)

---

## Part 1: Jac Quick Guide

Work through the Jac Quick Guide at:

> [https://docs.jaseci.org/quick-guide/](https://docs.jaseci.org/quick-guide/)

This guide will walk you through:

- Installing Jac via pip
- Set up your VSCode environment with Jac plugin.
- Writing and running your first Jac program
- Understanding core Jac concepts and the motivations behind the language
- Navigating the Jac documentation and ecosystem

Make sure you have a working Jac installation before moving on to Part 2.

---

## Part 2: Build Your First App Tutorial

Complete the three-part "Build Your First App" tutorial at:

> [https://docs.jaseci.org/tutorials/](https://docs.jaseci.org/tutorials/)

The tutorial consists of:

- **Part 1 -- Todo App with Graph Persistence**: Build a functional todo application from scratch, learning core Jac concepts including nodes, edges, walkers, and reactive frontends.
- **Part 2 -- Adding AI Capabilities**: Integrate LLM-powered features into the app using Jac's byLLM system, including enumeration types and structured AI outputs.
- **Part 3 -- Authentication and Project Structure**: Add user authentication, implement walkers for multi-user support, and organize the project into a clean multi-file structure.

At the end of this tutorial you will have a working, AI-enhanced todo application with user authentication.

---

## Part 3: Add Your Own Feature

This is the creative portion of the assignment. You must add **one new feature** of your choosing to the todo app you built in Part 2. The feature should be non-trivial and demonstrate that you understand how the Jac codebase works.

### Feature Ideas (you are not limited to these)

- **Due dates and reminders** -- Add date fields to todos and highlight overdue items
- **Priority levels** -- Allow users to assign and sort by priority (high/medium/low)
- **Categories or tags** -- Let users organize todos into categories or apply tags with filtering
- **Search and filter** -- Implement text search across todos and filtering by completion status
- **Recurring tasks** -- Support tasks that automatically re-create on a schedule
- **Subtasks** -- Allow todos to have nested subtasks with independent completion tracking
- **AI-powered task suggestions** -- Use byLLM to suggest task breakdowns or next steps
- **AI auto-categorization** -- Use the LLM to automatically categorize or tag new todos
- **Collaborative todos** -- Allow multiple users to share and collaborate on todo lists
- **Data export** -- Add functionality to export todos as JSON, CSV, or markdown
- **Dark mode or theme switching** -- Add a UI theme toggle
- **Drag-and-drop reordering** -- Allow manual reordering of tasks in the UI

You may propose and implement any feature not on this list. Creativity is encouraged.

---

## Submission Requirements

### GitHub Repository

1. Create a **public GitHub repository** containing your completed project
2. The repository must include:
   - All source code for the todo app with your custom feature
   - A `README.md` at the root of the repo that includes:
     - Your name and UMID
     - A brief description of the feature you added
     - Instructions on how to install and run the application
     - A short explanation of how your feature works and where the relevant code is located

### Canvas Submission

Submit the following on Canvas:

- The URL to your public GitHub repository

---

## Expectations

- **Tutorial completion** -- App runs and includes all functionality from Parts 1-3 of the tutorial (todo CRUD, AI integration, authentication)
- **Custom feature implementation** -- Feature is functional, non-trivial, and integrates cleanly with the existing app
- **Code quality** -- Code is readable, well-organized, and follows patterns established in the tutorial
- **README and documentation** -- Repository README clearly describes the feature, how to run the app, and where to find relevant code
- **Creativity and ambition** -- Feature goes beyond a minimal addition and shows genuine engagement with the Jac ecosystem (This is where 2-3% EC becomes achievable)

---

## Tips

- Start early. Getting your environment set up and working through the tutorial takes time.
- Commit frequently to your GitHub repo so your progress is visible.
- If you run into issues with Jac installation or the tutorials, ask for help in the help section of the [Jaseci Discord](https://discord.gg/jaseci) or [GitHub Issues](https://github.com/Jaseci-Labs/jaseci/issues).
- Focus on getting a clean, working feature rather than an ambitious but broken one.
- Test your app thoroughly before submitting, make sure everything works from a fresh clone of your repo.
