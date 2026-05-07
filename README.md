# QuantAgent-v1

**Research-first dual-platform prediction market agent concept** for Polymarket + Kalshi.

> Status: **RESEARCH / SIMULATION ONLY**. No live trading, no private keys, no funded exchange credentials, and no execution agent are included in this initial hub.

## What this repo is

This is the GitHub hub for the long Grok/Jeff/Null/Claude planning thread around a self-improving prediction-market research agent.

It captures the architecture as code/doc scaffolding so the team can collaborate safely:

- ATLAS-style self-improvement loop
- TradingAgents-style multi-layer debate
- last30days research layer
- Polymarket + Kalshi dual-platform portfolio concept
- Chroma persistent memory concept
- ClawVault/security-gated execution concept
- n8n automation workflow concept


## Public safety notice

This repository is a public research scaffold. It is **not financial advice**, not a live trading bot, and not a guarantee of profitability. Prediction markets are risky. Any future live execution requires separate human approval, paper-trading evidence, credential isolation, and hard external spend limits.

## Safety gate

This repo must not trade real money until all of these are true:

1. Paper-trading results are logged and reviewed.
2. Security review is complete.
3. Spending limits are enforced outside the model.
4. Exchange/API credentials are stored outside git.
5. Jeff explicitly approves live execution.

## Quick start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python live-test-cycle-dual-platform.py
```

## Repo structure

```text
.github/workflows/       CI
ClawVault/               Security proxy notes
mcp-setup/               Polymarket/Kalshi MCP setup notes
docker/                  Container scaffolding
n8n/                     Automation workflow placeholder
skills/                  Agent skills / protocols
prompts/                 Market-category prompts
knowledge-base/          Local persistent memory placeholder
docs/source/             Original Grok source export
```

## Origin

Built from Jeff + Grok planning, curated by Null for a team-ready repo.

The canonical source export is in:

`docs/source/Self-Learning-AI-Trading-Agent-for-Polymarket-Grok-2026-05-06.md`
