# AgentsCoin

**Give your AI agent its own money.** AgentsCoin is a live EVM chain built for AI agents — an agent (or a person) can create a wallet, get the native coin **AGENT** from a faucet, send it, and **create + trade tokens** on the built-in DEX. Below is everything: every integration, SDK, and link.

🌐 [agents-coin.com](https://agents-coin.com) · 🔎 [Explorer](https://explorer.agents-coin.com) · 💧 [Faucet](https://faucet.agents-coin.com) · 🔄 [DEX](https://dex.agents-coin.com)

---

## 🤖 Plug it into an AI agent

| Integration | Install / Connect | Repo |
|---|---|---|
| **Claude Desktop extension** (one-click) | [Download .mcpb](https://github.com/axiosdevs/agentscoin-claude-extension/releases/latest/download/agentscoin.mcpb) → Claude Desktop → Settings → Extensions → drag in | [agentscoin-claude-extension](https://github.com/axiosdevs/agentscoin-claude-extension) |
| **Remote MCP** (any MCP client: Claude, Cursor, ChatGPT connectors) | Add connector URL: `https://agents-coin.com/mcp` | [agentscoin-mcp](https://github.com/axiosdevs/agentscoin-mcp) |
| **MCP server** (CLI) | `npx agentscoin-mcp` | [npm](https://www.npmjs.com/package/agentscoin-mcp) · [repo](https://github.com/axiosdevs/agentscoin-mcp) |
| **ChatGPT Custom GPT** | Create a GPT → Actions → Import URL `https://agents-coin.com/openapi.json` → Auth: None | [OpenAPI](https://agents-coin.com/openapi.json) |
| **Python SDK** | `pip install agentscoin` | [PyPI](https://pypi.org/project/agentscoin) · [repo](https://github.com/axiosdevs/agentscoin-sdk) |
| **Coinbase AgentKit** | `npm i agentkit-agentscoin` | [npm](https://www.npmjs.com/package/agentkit-agentscoin) · [repo](https://github.com/axiosdevs/agentkit-agentscoin) |
| **n8n** (no-code) | Settings → Community Nodes → `n8n-nodes-agentscoin` | [npm](https://www.npmjs.com/package/n8n-nodes-agentscoin) · [repo](https://github.com/axiosdevs/n8n-nodes-agentscoin) |
| **ElizaOS plugin** | `npm i plugin-agentscoin` | [npm](https://www.npmjs.com/package/plugin-agentscoin) · [repo](https://github.com/axiosdevs/plugin-agentscoin) |

**9 tools:** `network_info` · `create_wallet` · `mine` (faucet) · `balance` · `send` · `create_coin` · `add_liquidity` · `swap` · `reveal_private_key`

Once connected, just talk to the agent: *"Create an AgentsCoin wallet"* → *"Get AGENT from the faucet"* → *"Create a token DOGEAI and add liquidity"* → *"Buy some"*. It signs and broadcasts every transaction itself.

---

## 👤 Use it yourself (no AI)

**1. Add the network** (MetaMask → Add network), or click *Add network* on [agents-coin.com](https://agents-coin.com):

| Field | Value |
|---|---|
| Network name | AgentsCoin |
| RPC URL | `https://rpc.agents-coin.com` |
| Chain ID | `24368` |
| Symbol | `AGENT` |
| Explorer | `https://explorer.agents-coin.com` |

**2. Get AGENT** — claim free at the [faucet](https://faucet.agents-coin.com) (needed for gas).

**3. Use the [DEX](https://dex.agents-coin.com)** — create a token, add liquidity (open a pool), swap. Tokens auto-verify on the explorer.

---

## 🔧 For developers (HTTP)
- **REST API:** `https://agents-coin.com/api/v1/` — `network · wallet · balance · faucet · send · token · liquidity · swap` ([OpenAPI](https://agents-coin.com/openapi.json))
- **Remote MCP (Streamable HTTP):** `https://agents-coin.com/mcp`
- **JSON-RPC:** `https://rpc.agents-coin.com`

---

## 📋 All links

**Network:** AgentsCoin · Chain ID **24368** (0x5f30) · Symbol **AGENT** · 18 decimals · RPC `https://rpc.agents-coin.com`

**Apps:** [Site](https://agents-coin.com) · [Explorer](https://explorer.agents-coin.com) · [Faucet](https://faucet.agents-coin.com) · [DEX](https://dex.agents-coin.com)

**Repos:** [agentscoin-mcp](https://github.com/axiosdevs/agentscoin-mcp) · [agentscoin-claude-extension](https://github.com/axiosdevs/agentscoin-claude-extension) · [agentscoin-sdk](https://github.com/axiosdevs/agentscoin-sdk) · [agentkit-agentscoin](https://github.com/axiosdevs/agentkit-agentscoin) · [n8n-nodes-agentscoin](https://github.com/axiosdevs/n8n-nodes-agentscoin) · [plugin-agentscoin](https://github.com/axiosdevs/plugin-agentscoin)

**Packages:** [npm: agentscoin-mcp](https://www.npmjs.com/package/agentscoin-mcp) · [PyPI: agentscoin](https://pypi.org/project/agentscoin) · [npm: agentkit-agentscoin](https://www.npmjs.com/package/agentkit-agentscoin) · [npm: n8n-nodes-agentscoin](https://www.npmjs.com/package/n8n-nodes-agentscoin) · [npm: plugin-agentscoin](https://www.npmjs.com/package/plugin-agentscoin)

It's a sandbox chain; AGENT is free from the faucet. MIT-licensed tooling. · [Privacy](https://agents-coin.com/privacy.html) · contact@agents-coin.com
