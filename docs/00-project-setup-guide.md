# Living Process Guide: AI-Assisted Project Setup

## Core Philosophy: Play First, Prototype First, Then Productionize
- Avoid old-school "plan everything for months before building" paralysis.
- Start by batting ideas around with AI to build a fast, working prototype and discover what the application truly needs.
- Once the prototype proves out the real requirements, transition immediately into structured, production-level software development on GitHub.

## Stage 1: Play & Rapid Prototyping (AI Studio)
- Explore features, edge cases, and calculations conversationally in AI Studio until you have a working prototype.
- Capture the proven logic, screen flows, and edge cases you uncovered.

## Stage 2: Create the GitHub Repository First
- Before pushing code or docs, create the repository on GitHub first (for example, `project-starter-template` or your new project repo) so a remote target already exists.
- Leave initialization options (like an extra README) blank if you are pushing a local starter folder so your initial history stays clean.

## Stage 3: Run AI-Generated PowerShell Setup & Push to GitHub
- Ask AI for the exact PowerShell commands to create folders (`docs/`, `data/`, etc.) and write starter files (`README.md`, specs, sample JSON data) so you paste and run instead of typing boilerplate by hand.
- Initialize Git locally (if new), connect `origin` to your GitHub repository URL, commit your work, and run `git push -u origin main`.
- Place reference files (such as the walkthrough presentation deck in the root folder) where needed, then commit and push again.

## Stage 4: Codify Specs, Build in AI Studio & Update This Guide
- Translate proven prototype rules into structured Markdown specs (`docs/`) and baseline test fixtures (`data/`).
- Attach your `docs/` and `data/` files in AI Studio and VS Code to build out the production application.
- Whenever you add a new stage, fix a workflow snag, or learn a better pattern, update `docs/00-project-setup-guide.md` and refresh the root presentation deck, then commit and push.
