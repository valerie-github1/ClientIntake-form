# PhoennixAI Client Intelligence Intake

> **Client brief form for PhoennixAI onboarding.**
> Single-file HTML — no server, no dependencies, deploys anywhere in 60 seconds.

**Live:** [phoennixai-client-intake.vercel.app](https://phoennixai-client-intake.vercel.app)

---

## What it does

Collects a structured intelligence brief from prospective PhoennixAI clients across five sections: contact details, organisation profile, current challenges, AI & technology readiness, and 90-day goals.

On submission, the client's email app opens with a fully pre-formatted brief addressed to `valerie@phoennixai.com` (CC: `phoenixdigitec3@gmail.com`). No backend required.

---

## Features

- 5-section intake covering contact, business profile, pain points, AI readiness, and goals
- Booking strip linking to `cal.com/phoennixai/beta-discovery` for clients who prefer a call
- Progress bar tracking required field completion
- Auto-generated reference number (`PAI-2026-XXXX`) per submission
- Branded success screen with explicit "Send Your Brief" action button
- Fully offline-capable — works as a local file or deployed URL
- Print-ready (no console, no build step)

---

## Deployment

### Option A — Vercel (recommended, permanent URL)

1. Upload `index.html` (renamed from `ClientIntake_v4.html`) to this repo
2. Connect repo to [vercel.com](https://vercel.com) → New Project → Import
3. Framework preset: **Other**
4. Deploy — live in under 90 seconds

Every push to `main` auto-deploys.

### Option B — Local test

Open `ClientIntake_v4.html` directly in Chrome. All features work locally.

---

## How submissions arrive

No server or API key needed. On submit:

1. Success screen appears with the client's reference number
2. The client's default email app opens automatically with the brief pre-filled
3. Client clicks **Send** inside their email app
4. Brief arrives at `valerie@phoennixai.com` with `phoenixdigitec3@gmail.com` CC'd

**Subject line format:** `New Client Brief — [Name] | [Company] | REF: PAI-2026-XXXX`

If the email app does not open automatically, the **Send Your Brief →** button on the success screen triggers it manually.

---

## File structure

```
/
├── index.html          # The complete intake form (rename from ClientIntake_v4.html)
└── README.md           # This file
```

Single file. No `node_modules`. No build. No config.

---

## Brand

Built to the PhoennixAI brand system v1.1:

- **Colours:** Off-white `#F7F6F2` · Ink `#1F2426` · Olive `#ABA944`
- **Fonts:** Agdasima (display) · Source Serif 4 (body) · Fira Code (mono)
- **Tagline:** Created to Create. Intelligent by nature.

---

## Related

| Product | Repo | URL |
|---|---|---|
| Mission Control | `phoennixai-mission-control` | phoennixai-mission-control-eight.vercel.app |
| Beta Onboarding App | `client-intake-bay` | client-intake-bay.vercel.app |
| RYD Client Platform | `ryd_client_app` | ryd-client-app-ashy.vercel.app |

---

**PhoennixAI Ltd · Company Reg. 16795610 · London, UK**
`info@phoennixai.com` · `www.phoennixai.com`
