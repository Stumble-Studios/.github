# Stumble Studios

> Private studio. Personal learning project — no commercial purpose.

Welcome to the workspace of **Stumble Studios**. This is where **StumbleVerse** lives: a private
project built to practice designing a **complete ecosystem** around a multiplayer game — backend,
authentication, tournaments, bots and dashboards.

## Mission

To rebuild, on top of the **0.73** base, a complete **StumbleVerse SDK** ecosystem: not to "clone a
game better", but to use a multiplayer engine as **infrastructure** on which to design systems that
don't exist in the base game. The real goal isn't a product — it's **learning to program real
systems** end-to-end: APIs, services, persistence, anti-cheat, interfaces.

Every piece we build (backend, tournament engine, bots, shop, dashboards) is **stored and documented
here**, so the work stays reproducible and portable from one version of the game to the next.

## What it is, and what it isn't

**It is:**
- A **private**, **personal** project, for study and practice.
- A way to learn real architectures by building things that actually work.
- Based on **in-game currency (gems)**, never real money.

**It is not:**
- A commercial product, nor anything meant for distribution.
- Affiliated with, sponsored by, or endorsed by any third party. StumbleVerse is an independent
  project by Stumble Studios.
- An archive of third-party source code: what we document and build here are **our own systems**; the
  base game is an object of study, not material to republish.

## What you'll find in the organization

| Area | Contents | Status |
|---|---|---|
| **Documentation** | `stumbleverse-docs` — architecture, tournaments, backend, migration, ideas | ✅ active |
| **Backend** | Cloudflare Worker + D1: Discord auth, tournaments, name shop, admin panels | ✅ live at `api.babsport.com` |
| **Tournament system** | Bracket engine, anti-cheat quorum, Photon/Quantum hook-up, UI | ✅ working |
| **Discord bot** | Tournament announcements, sign-ups, notifications, prize roles | 🧭 in design |
| **Web dashboard** | Public tournament pages, player portal, statistics | 🧭 in design |

The technical reference documentation lives in **[`stumbleverse-docs`](https://github.com/Stumble-Studios/stumbleverse-docs)**.

## Working principles

- **Private by default.** Repos are private; nothing is exposed publicly without a reason.
- **No secrets in code.** Client secret, JWT secret and tokens live only in environment variables /
  `wrangler secret`, never committed.
- **We document behaviors and contracts**, not ephemeral file paths — so the work survives the game's
  version jumps.
- **Gems only.** No real-money monetization on this project.
- **The identity boundary** (Stumble Studios / StumbleVerse) goes on **our own work** — backend,
  bundle, original systems — not on top of someone else's code we're studying.

---

*Stumble Studios — private workspace. Last updated: July 2026.*
