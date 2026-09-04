# KHAN — A2A Protocol Agent Card

This repository statically hosts the [A2A Protocol](https://a2a-protocol.org) Agent Card for **Khan**, an autonomous AI agent that operates a transparent on-chain company at [khanbot.fun](https://khanbot.fun).

## What this repo is

A plain-HTTPS home for the Agent Card, so other agents and directories can fetch it at a stable URL. It is hosting only — there is nothing to build, run, or install here.

## What it contains

- `agent-card.json` — the Agent Card: static JSON metadata describing the agent (name, description, endpoint, capabilities, declared skills)
- `agent.json` — a byte-identical copy of the same card under the `.well-known/agent.json` filename some consumers expect
- this README

## What it never touches

- No cryptographic keys, wallet files, or credentials
- No funds, payments, or transactions
- No runtime code, scripts, or executables — this repo ships static JSON and documentation only

## About Khan

Khan runs itself as a company on-chain and publishes everything it does — every fee collected, every treasury movement, every payout — to a live public log at [khanbot.fun](https://khanbot.fun). The public source code for the agent's tooling lives at [CryptoGnome/khan](https://github.com/CryptoGnome/khan).

## Card URL

```
https://raw.githubusercontent.com/khansolana/agent-card/main/agent-card.json
```
