# Zach Bird 🐦

Austin, TX. I architect and operate AI agent systems — and ship real products with them.

Most of the code in my repos is agent-built **by design**: I do the architecture, review, and operations; a self-hosted fleet of AI agents does the execution. Running that loop well — reliably, safely, in production — is the craft I care about.

The load-bearing design is mine: the SSE ↔ LangGraph streaming bridge in the [Council Terminal](https://github.com/zachthebird/council-terminal#whats-mine-vs-whats-upstream), the SQLite kanban dispatch schema and multi-provider failover routing, and the money-gate model that lets agents act autonomously only under a hard spend ceiling. The Council Terminal spells out [what's mine vs. what's upstream](https://github.com/zachthebird/council-terminal#whats-mine-vs-whats-upstream) explicitly.

## What I'm running

**A self-hosted multi-agent fleet (24/7, on macOS).** Role-specialized agents — project management, web dev, finance, comms — with launchd-supervised gateways, kanban-based task dispatch, and multi-provider model routing with automatic failover (Claude, Gemini, DeepSeek). Human-in-the-loop gates on anything that spends money.

Things the fleet ships and operates:

- 🛍️ **[BusyBird](https://busybirdaustin.com)** — 3D-printed jewelry storefront (plus an Etsy channel): Next.js App Router, Stripe Checkout, Tailwind 4 → [repo](https://github.com/zachthebird/busybird-store)
- 📈 **[Council Terminal](https://github.com/zachthebird/council-terminal)** — a retro **PC-98 anime terminal** for the [TradingAgents](https://github.com/TauricResearch/TradingAgents) multi-agent LLM framework: an eight-agent council researches a ticker, the bull and bear debate live (SSE), and the judge rules BUY/SELL/HOLD → [live demo](https://zachbird.com/tradingAgentsGUI/)
- 🌐 **Client & personal sites** — designed, built, deployed, and DNS-managed end-to-end on Vercel by the web-dev agent team
- 💬 **SMS agent** on Twilio behind a Cloudflare tunnel
- 🧾 **Ceiling-gated autonomous payments** with receipts reported to Telegram
- 📖 **[agent-fleet-ops](https://github.com/zachthebird/agent-fleet-ops)** — the open field manual for running the fleet: launchd supervision, SQLite kanban dispatch, multi-provider failover, hard gates on money

## Stack

TypeScript · Next.js · React · Node · Python · FastAPI · SQLite · launchd · Vercel · Stripe · Twilio · Claude · Gemini · DeepSeek

## Find me

[zacharybird.com](https://zacharybird.com) · [LinkedIn](https://linkedin.com/in/zacharybird) · [email](mailto:email@zachbird.com)

> Open to AI product / applied-AI / founding roles.

<!-- fleet-maintained -->
