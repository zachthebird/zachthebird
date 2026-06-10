# Zach Bird 🐦

Austin, TX. I architect and operate AI agent systems — and ship real products with them.

Most of the code in my repos is agent-built **by design**: I do the architecture, review, and operations; a self-hosted fleet of AI agents does the execution. Running that loop well — reliably, safely, in production — is the craft I care about.

## What I'm running

**A self-hosted multi-agent fleet (24/7, on macOS).** Role-specialized agents — project management, web dev, finance, comms — with launchd-supervised gateways, kanban-based task dispatch, and multi-provider model routing with automatic failover (Claude, Gemini, DeepSeek). Human-in-the-loop gates on anything that spends money.

Things the fleet ships and operates:

- 🛍️ **[BusyBird](https://busybird-store.vercel.app)** — 3D-printed jewelry storefront: Next.js App Router, Stripe Checkout, Tailwind 4 → [repo](https://github.com/zachthebird/busybird-store)
- 📈 **[The Bazaar](https://github.com/zachthebird/the-bazaar)** — a character-driven GUI for the [TradingAgents](https://github.com/TauricResearch/TradingAgents) multi-agent LLM trading framework: summon an analyst team, watch Bull vs. Bear debate live (SSE) as game-style personas, get a verdict → [live demo](https://static-demo-gules.vercel.app)
- 🌐 **Client & personal sites** — designed, built, deployed, and DNS-managed end-to-end on Vercel by the web-dev agent team
- 💬 **SMS agent** on Twilio behind a Cloudflare tunnel
- 🧾 **Ceiling-gated autonomous payments** with receipts reported to Telegram

## Stack

TypeScript · Next.js · React · Node · Python · FastAPI · SQLite · launchd · Vercel · Stripe · Twilio · Claude · Gemini · DeepSeek
