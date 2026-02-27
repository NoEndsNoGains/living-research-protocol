# Claude Code + Obsidian: Mobile Workflow Guide

**Status:** Research note — approaches evaluated Feb 2026
**Goal:** Use voice/phone to talk to Claude → Claude intelligently updates Obsidian vault
**Context:** iPhone user, free-tier Obsidian (no Obsidian Sync), this repo already contains LRP markdown files

---

## The Problem

Obsidian on iPhone only syncs via:
- **iCloud** (free but unreliable, especially with Git repos)
- **Obsidian Sync** (paid, $4/month)

Getting Claude Code to directly manage an Obsidian vault from a phone is not a single-tool solution — it requires connecting three things: voice input, AI agent, and file sync.

---

## Three Approaches Evaluated

### Approach A: Claude Anywhere (Tailscale Relay)

**How it works:** Obsidian plugin streams your Mac's Claude Code session to mobile devices over secure Tailscale connection.

**Requirements:**
- Mac with Claude Code installed (must stay awake)
- Tailscale on both Mac and iPhone (free, same account)
- File sync between Mac and phone (iCloud, Dropbox, or Obsidian Sync)

**Setup:**
1. Install Tailscale on Mac and iPhone
2. Install Claude Anywhere plugin in Obsidian on Mac
3. Enable "Remote Access" in plugin settings
4. Keep Mac awake (`caffeinate -dis` in Terminal, or Amphetamine app)
5. On iPhone: connect via Tailscale, open Claude from Obsidian command palette

**Pros:**
- Full Claude Code access from phone
- Claude edits files directly on Mac — no sync lag
- Obsidian sees changes immediately

**Cons:**
- Mac must stay awake and connected
- Mobile terminal UI is awkward (no real keyboard)
- Session dies on disconnect (use `/resume` to recover)

**Source:** [obsidian-claude-anywhere](https://github.com/derek-larson14/obsidian-claude-anywhere)

---

### Approach B: Git-Synced Vault (Claude Vault / DIY)

**How it works:** Vault lives in a Git repo. Claude Code pushes changes. Phone pulls them. Both human and AI work on the same files.

**Requirements:**
- GitHub repo (this repo already qualifies)
- Claude Code (web session, CLI, or remote)
- On iPhone: Working Copy app ($20 one-time) or Git client

**Setup:**
1. Open this repo as an Obsidian vault on desktop
2. Use Claude Code (web or CLI) to manage files — it commits and pushes
3. On iPhone: clone repo in Working Copy, open in Obsidian via "Open folder as vault"
4. Pull changes on phone when needed

**Alternatively (simpler phone side):**
- Skip Obsidian on phone entirely
- Use Working Copy or a file browser to view markdown files
- Use Claude mobile app (voice mode) to dictate what changes to make
- Claude Code in a web session makes the actual edits to the repo

**Pros:**
- Already works with this repo's existing structure
- No always-on Mac required
- Full version history via Git
- Claude Code web sessions are accessible from any device

**Cons:**
- Not real-time sync (requires commit/push/pull cycle)
- Working Copy costs $20 (but one-time, not subscription)
- Two-step process: talk to Claude → then pull on phone

**Source:** [claude-vault](https://github.com/ksanderer/claude-vault)

---

### Approach C: Server-Based Claude Code

**How it works:** Claude Code runs on a remote server. Access from phone via browser or SSH. Files live on the server and sync outward.

**Requirements:**
- VPS or cloud server (or always-on home machine)
- SSH client or web terminal on phone
- Sync mechanism (Git, rsync, etc.)

**Setup:**
1. Set up a Linux server (e.g., $5/month DigitalOcean droplet)
2. Install Claude Code CLI on the server
3. Clone this repo on the server
4. SSH in from phone (Termius, Blink, or similar)
5. Run Claude Code, make changes, push to GitHub
6. Pull on desktop Obsidian when needed

**Pros:**
- Always available, no Mac dependency
- True "remote agent" — Claude works on the server
- Skip sync problem entirely (files live where Claude runs)

**Cons:**
- Requires server setup and maintenance
- Monthly cost for VPS
- SSH on phone is workable but not pretty

---

## Recommended Workflow (Simplest Path)

For the specific use case of **talking to Claude while driving**:

```
Voice (Phone)  →  Claude Mobile App  →  Describe what you want
                         ↓
              Claude Code Web Session  →  Edits markdown files in this repo
                         ↓
                    Git push  →  GitHub
                         ↓
              Desktop Obsidian  →  Git pull to see changes
```

**Why this works:**
1. Claude mobile app already has voice mode — just talk
2. Claude Code web sessions can access this GitHub repo directly
3. No iCloud, no Obsidian Sync, no Tailscale needed
4. Desktop Obsidian just opens the local Git clone of this repo

**The missing link is connecting Claude mobile voice to Claude Code web sessions.** Currently these are separate — you'd need to:
- Dictate to Claude mobile what changes you want
- Then open a Claude Code web session to execute them
- OR use Claude Code on the web directly from your phone browser

---

## MCP Plugin Option (Desktop Enhancement)

For desktop use, the **obsidian-claude-code-mcp** plugin connects Claude Code directly to your Obsidian vault via Model Context Protocol:

- Auto-discovers your vault via WebSocket
- Provides file operations (view, edit, create, insert)
- Gives Claude workspace context (current file, all files)
- Default port: 22360

**Source:** [obsidian-claude-code-mcp](https://github.com/iansinnott/obsidian-claude-code-mcp)

---

## Tools Referenced

| Tool | Type | Cost | Link |
|------|------|------|------|
| Claude Anywhere | Obsidian plugin | Free | [GitHub](https://github.com/derek-larson14/obsidian-claude-anywhere) |
| Claude Vault | Template repo | Free | [GitHub](https://github.com/ksanderer/claude-vault) |
| Obsidian Claude Code MCP | Obsidian plugin | Free | [GitHub](https://github.com/iansinnott/obsidian-claude-code-mcp) |
| Claudian | Obsidian plugin | Free | [GitHub](https://github.com/YishenTu/claudian) |
| Tailscale | VPN/networking | Free tier | [tailscale.com](https://tailscale.com) |
| Working Copy | iOS Git client | $20 one-time | App Store |

---

## What This Repo Needs to Work as an Obsidian Vault

This repo (`living-research-protocol`) is already a collection of markdown files — it's vault-ready. To use it with Obsidian:

1. Clone the repo locally
2. Open Obsidian → "Open folder as vault" → select the repo folder
3. Obsidian will create a `.obsidian/` config directory (add to `.gitignore`)
4. All existing `.md` files become browsable, linkable notes

**Note:** The files with `#` in their names (e.g., `# LRP Design Note 0: ...`) may cause issues on some filesystems. Consider renaming them without the leading `#` for cross-platform compatibility.

---

*This guide was created during the claude/claude-code-obsidian-sync exploration. Updated as approaches are tested.*
