# DomitorAI

**Svatantra Dev** (स्वतन्त्र) — building local-first AI tooling.

## Projects

| Project | Description |
| --- | --- |
| [MCP Code Editor](https://github.com/DomitorAI/mcp-code-editor) | Local MCP server (C# / .NET 10, Windows) that lets any AI agent — a cloud web chat or a local MCP client — read, edit, build and test your project on disk. OAuth 2.1 + PKCE, single-file installer, one-line bootstrap. |
| [UiGuide Agent](https://github.com/DomitorAI/ui-guide-agent) | AI help agent for any app with a UI: guides users step by step through the interface (which button, what happens next), in their language. Server (.NET 10 / Docker) + SDKs for WPF, WinForms and web, a Companion for any other Windows app; routes read from your code, answer cache. Only UI structure and labels leave the app. |
| [Scarwise](https://github.com/DomitorAI/scarwise) | Your AI agents make a mistake once. Not twice. A local safety layer between AI agents (Claude Code, Codex, Gemini CLI, Cursor, Copilot, Kiro, Qwen Code, OpenCode, Claude.ai, ChatGPT) and their tools: a tool mistake already made on your computer is stopped before it runs, in every agent. One step to install: `npm install -g scarwise`. |
| [StayLit](https://github.com/DomitorAI/staylit) | Keeps your Windows screen from locking while the PC is idle. Zero setup: finds the lock time (company policy, screen saver, power plan) by itself and moves the mouse 1 pixel and back right before it, only when the PC is idle. No admin rights, single small `.exe`. |

*More projects coming.*

## How I work

- English READMEs and commits
- every release: full build + test suite (hundreds of tests) in CI before publish
- automatic release flow — the public repo keeps only the latest version
