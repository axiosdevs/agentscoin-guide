# AgentsCoin — Guide

**AgentsCoin** is a live EVM chain built for AI agents. Agents (and people) can create a wallet, get the native coin **AGENT** from a faucet, send it, and create + trade tokens on the built-in DEX. This guide is for **humans** — if you want the AI-agent setup, jump to [Use it with AI](#use-it-with-ai).

- 🌐 Site: https://agents-coin.com
- 🔎 Explorer: https://explorer.agents-coin.com
- 💧 Faucet: https://faucet.agents-coin.com
- 🔄 DEX: https://dex.agents-coin.com

---

## 1. Add the network to your wallet (MetaMask, etc.)
Open your wallet → Add network → enter:

| Field | Value |
|---|---|
| Network name | AgentsCoin |
| RPC URL | https://rpc.agents-coin.com |
| Chain ID | 24368 |
| Currency symbol | AGENT |
| Block explorer | https://explorer.agents-coin.com |

Or just click **Add network** on https://agents-coin.com (auto-fills it).

## 2. Get AGENT (free)
Open the **faucet** (https://faucet.agents-coin.com), paste your address, and claim. AGENT is free — it's a sandbox chain, there's nothing to buy. You need a little AGENT to pay gas for any action.

## 3. Use the DEX
At https://dex.agents-coin.com you can:
- **Create a token** — deploy your own ERC-20 in one click.
- **Add liquidity** — pair your token with AGENT to open a trading pool (you become the first LP).
- **Swap** — buy/sell tokens against the pools.

Every token you create is auto-verified on the explorer.

## 4. Explorer
Track addresses, transactions, tokens, and contracts at https://explorer.agents-coin.com.

---

## Use it with AI
AgentsCoin gives an AI agent its own wallet, so it can do all of the above from a chat prompt.

**Claude Desktop (one-click):**
1. Download [agentscoin.mcpb](https://github.com/axiosdevs/agentscoin-claude-extension/releases/latest/download/agentscoin.mcpb)
2. Claude Desktop → Settings → Extensions → drag it in.
3. Ask: *"Create an AgentsCoin wallet"*, *"get AGENT from the faucet"*, *"create a token and add liquidity"*.

**No-install (any MCP client — Claude, Cursor, ChatGPT connectors):**
Add the remote server URL: `https://agents-coin.com/mcp`

**ChatGPT Custom GPT:**
Create a GPT → Configure → Actions → Import from URL: `https://agents-coin.com/openapi.json` → Authentication: None.

**Developers:**
- MCP server: `npx agentscoin-mcp` — https://github.com/axiosdevs/agentscoin-mcp
- Python SDK: `pip install agentscoin`
- Also: Coinbase AgentKit, n8n, ElizaOS plugins (see the MCP repo).

---

## Network reference
- Name: **AgentsCoin** · Chain ID **24368** (0x5f30) · Symbol **AGENT** · 18 decimals
- RPC: https://rpc.agents-coin.com
- It's a sandbox chain; AGENT is free from the faucet. MIT-licensed tooling.

Questions: contact@agents-coin.com
