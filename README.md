# 🏛️ governanceOracle

**DORA Execution MCP Server** — 10 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-10-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)
![Bus](https://img.shields.io/badge/Oracle_Bus-Connected-00C853?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/governance/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "governanceoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/governance/mcp/"]
    }
  }
}
```

## Tools (10)

| Tool | Description |
|------|-------------|
| `register_finding` | Register an audit finding, risk, or control gap. |
| `list_findings` | List findings with optional filters. |
| `board_report` | Generate Management Body review pack — executive summary, open findings, risk po |
| `framework_review` | ICT Risk Management Framework annual review — effectiveness assessment per DORA  |
| `control_status` | Control effectiveness dashboard across all DORA control domains. |
| `exception_register` | View or add risk acceptances / exceptions with expiry tracking. |
| `action_tracker` | Track remediation actions with deadlines and ownership. |
| `kpi_dashboard` | ICT Risk KPIs — open findings, overdue rate, remediation rate, exception count. |
| `annual_review` | Annual framework review evidence bundle — checklist, stats, Art. 6(5) compliance |
| `health_check` | Server status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

governanceOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.

### DORA Coverage

**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/governance/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
