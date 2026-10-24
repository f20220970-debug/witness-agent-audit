# Witness: an independent auditor for the AI agent that shops for you

**Live prototype:** https://f20220970-debug.github.io/witness-agent-audit/ · **Case document:** [Witness_product_case.pdf](case/Witness_product_case.pdf)

A product case on personal AI agents in 2040: when an agent buys on your behalf, seller and platform agents can
nudge it with offers, paid placement and emotional signals the user never sees. **Witness** is a user-owned audit
agent that watches your shopping agent and turns thousands of opaque decisions into a few human-sized signals.

## What's in the case
1. **Ramifications** of the 2040 agent paradigm, scored on reach, harm, invisibility and solvability; agent-to-agent
   commercial manipulation ranked first, because it also drives preference drift and the accountability gap.
2. **Problem and users:** a primary persona who delegates almost all buying, an older persona exposed to emotional
   nudges, and platforms that need to prove fair dealing; backed by cited survey evidence on agent trust and dark patterns.
3. **The product:** Influence Receipts, an Influence Score with a user-set threshold, Drift Alerts, plain-language
   Guardrails, Family Guardian, and a monthly self-check, built on a proposed open Agent Decision Record standard.
4. **Metrics:** north star = Endorsed Decision Rate (purchases the user would make again), with protection, engagement,
   adoption and counter-metrics (alerts per week, added latency).
5. **Risks, business model and roadmap.**

## The prototype
A single self-contained HTML file (no build step, no internet needed). It simulates one evening in the app:
- **Today:** 23 agent decisions, most approved silently; one flagged purchase and one blocked subscription.
- **Influence Receipt:** who shaped the flagged headphones purchase, the cheaper option the user would usually pick,
  and one-tap "I'd buy again" or "Undo & swap".
- **Drift alert:** electronics spend tripled after one seller's agent started engaging, with "was this intended?"
- **Guardrails:** toggle rules, write your own, set the alert threshold, and simulate a paid placement being blocked.

Open `index.html` in any browser, or use the live link above.

## Note
Personas, decisions and figures in the prototype are illustrative. Survey sources are listed in the case document's
appendix. Prepared as a product case submission for a campus APM process (October 2026).
