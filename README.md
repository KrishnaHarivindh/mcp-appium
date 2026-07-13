# AI-Driven QA Automation MCP Server

![CI](https://github.com/KrishnaHarivindh/mcp-appium/actions/workflows/node-ci.yml/badge.svg)
![License](https://img.shields.io/github/license/KrishnaHarivindh/mcp-appium)
![Last Commit](https://img.shields.io/github/last-commit/KrishnaHarivindh/mcp-appium)
![Language](https://img.shields.io/github/languages/top/KrishnaHarivindh/mcp-appium)

Model Context Protocol server for AI-assisted QA automation, mobile app exploration, and test-case generation workflows.

## Overview

This repository is the MCP server foundation for my minor project, **AI-Driven Test Case Generation, Execution & Automation using MCP**.

The broader project connects requirements, UI context, test assets, and automation workflows into a human-reviewed QA lifecycle. This server exposes structured tools that AI assistants can use to inspect mobile apps, interact through Appium, collect context, and support test-case or automation-script generation.

## Use Cases

- AI-assisted mobile app exploration
- Appium command orchestration through MCP
- Requirement-to-test context gathering
- Test case generation support
- Automation script generation support
- Human-in-the-loop QA review workflows

## Minor Project Workflow

```text
Jira / requirements
  -> Figma / UI context
  -> Existing test assets
  -> MCP context and tool orchestration
  -> LLM-assisted test analysis
  -> QA reviewer approval
  -> Test case updates and automation scripts
```

The system is designed to keep humans in control of final QA decisions. AI-generated test cases and scripts should be reviewed, edited, and approved before being committed to a test management system or automation repository.

## Tech Stack

**Runtime:** Node.js  
**Automation:** Appium  
**Protocol:** Model Context Protocol  
**AI / QA:** LLM-assisted test generation, MCP tool orchestration, mobile testing workflows

## Project Structure

```text
mcp-appium/
  lib/                  MCP server and mobile automation implementation
  docs/                 Architecture notes
  package.json          Node package metadata
  package-lock.json     Locked dependencies
  LICENSE               License
```

## Setup

```bash
npm install
```

## Run

```bash
npm start
```

## Security Notes

- Do not commit Jira, Figma, Google, AIO, OpenAI, or mobile cloud credentials.
- Keep `.env`, `.env.local`, device dumps, screenshots, and runtime artifacts out of Git.
- Rotate any token that was stored in plain text before using this project publicly.

## Portfolio Note

This project demonstrates AI tooling integration, test automation architecture, MCP-based tool design, mobile QA automation, and end-to-end QA lifecycle thinking.
