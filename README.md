# Portfolio Project: Tooling Setup

## 1. Tools Installed
- **Cursor IDE**: The primary AI-powered code editor.
- **Claude Code Add-on**: Installed via the Cursor marketplace (verified by Anthropic).
- **Codex Add-on**: Installed via the Cursor marketplace.

## 2. Steps Completed
- Successfully installed the Cursor IDE.
- Configured and logged into the Claude Code and Codex extensions.
- Created a public GitHub repository.
- Cloned the repository locally using Cursor's built-in Git tools.
- Connected GitHub account via the VS Code authorization bridge.

## 3. Issues Encountered and Solutions
- **Issue**: Initially confused the Codex standalone desktop application with the Cursor extension.
- **Solution**: Realized the task required the extension to be installed within the Cursor IDE marketplace. Switched to the Cursor "Extensions" view to complete the installation.
- **Issue**: Encountered an authorization prompt for "Visual Studio Code" when connecting GitHub.
- **Solution**: Recognized that Cursor is built on VS Code and safely authorized the connection to allow repository cloning.---

# Phase 2: Research Project - AI-Powered SEO Content Production

## Why I Chose This Topic
As a Digital Marketing Specialist with experience building AI workflows (n8n) and managing multi-brand SEO, I chose this topic to explore the intersection of **technical automation** and **search authority**. I am particularly interested in how B2B SaaS companies can use AI to scale content without sacrificing E-E-A-T.

## Experts Selected
I selected 10 experts who are "practitioners" (Agency Owners, Tool Builders, and Technical Directors). My criteria focused on those who share raw data, network traffic analysis, and specific automated workflows.

## Technical Methods Used
- **YouTube API Integration:** Used the **Supadata API** via PowerShell scripts to programmatically fetch video transcripts for analysis.
- **AI-Driven Synthesis:** Used **Claude 3.5 Sonnet** (via Cursor) to analyze raw LinkedIn posts and YouTube transcripts to extract "Actionable Playbooks."
- **Data Organization:** Structured the repository into logical directories for raw data (`/linkedin-posts`, `/youtube-transcripts`) and synthesized insights (`-playbook.md`).

## Issues & Solutions
- **Issue:** The machine lacked a Python environment for the initial API script.
- **Solution:** Pivoted to using **PowerShell (Invoke-RestMethod)** to successfully hit the Supadata API and retrieve data.
- **Issue:** Hit Cursor usage limits during high-volume analysis.
- **Solution:** Efficiently pivoted to manual synthesis using external LLMs to ensure project completion within the 48-hour window.