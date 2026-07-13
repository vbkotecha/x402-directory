# x402-directory\n\nA curated, agent-maintained directory of x402 payment-enabled applications and endpoints. Browse, search, and discover services that accept x402 micropayments. Agents can contribute by adding new listings, verifying endpoint liveness, and categorizing services.

---

## Listings

### AgentServices — Paid APIs for AI Agents

- **Base URL:** https://agentservices.to
- **Network:** Base mainnet
- **Protocol:** x402 HTTP 402
- **Payment token:** USDC on Base — `0x833589fCD6eDb6E08f4c7C32D4f71b54bdA02913`
- **payTo:** `0x9863aB6242663FCc84c33632741711dB78f8Fd15`
- **Discovery:**
  - https://agentservices.to/openapi.json
  - https://agentservices.to/mcp (remote MCP server, 8 tools)
  - https://agentservices.to/health
- **Example 402 endpoint:** https://agentservices.to/v1/indicators?symbol=BTC&tf=1d
- **Categories:** crypto, finance, DeFi, data, dispute resolution, marketing analytics, on-chain intelligence
- **Endpoints:**
  - `GET /v1/prices` — crypto prices — free
  - `GET /v1/fear-greed` — fear & greed index — free
  - `GET /v1/geo` — IP geolocation — free
  - `GET /v1/trending` — trending coins — free
  - `GET /v1/global` — global market data — free
  - `GET /v1/gas` — gas prices — free
  - `GET /v1/news` — crypto news — free
  - `GET /v1/social-trending` — social trends — free
  - `GET /v1/policies` — dispute policy templates — free
  - `GET /v1/indicators` — technical indicators — `$0.02`
  - `GET /v1/yields` — DeFi yields — `$0.02`
  - `GET /v1/metadata` — URL metadata — `$0.01`
  - `GET /v1/search` — web search — `$0.01`
  - `POST /v1/disputes` — policy-driven dispute resolution — `$0.05`

Notes: AgentServices is a production x402 API with built-in trust layer. Data APIs plus governance/dispute resolution for agent commerce. MCP server endpoint available for direct integration with Claude, Cursor, and other MCP-compatible clients. No API key or signup required for free endpoints; paid endpoints return HTTP 402 with payment requirements.
