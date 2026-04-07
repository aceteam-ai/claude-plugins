# Anthropic Official Marketplace Submission

Submit at: https://platform.claude.com/plugins/submit
(or https://claude.ai/settings/plugins/submit)

---

## Plugin 1: aceteam

**Name:** aceteam

**Description:** Manage AI agents, knowledge bases, documents, and workbenches on AceTeam. Create, update, and chat with agents. Search knowledge bases and manage MCP server connections. Used by 150+ university students building AI consulting workflows.

**Category:** productivity

**Homepage:** https://aceteam.ai

**Source repository:** https://github.com/aceteam-ai/claude-plugins

**Source path:** plugins/aceteam

**Author:** AceTeam.ai (support@aceteam.ai)

**Why include in official marketplace:**

AceTeam is an AI agent orchestration platform used in university education programs (SJSU College of Business, 150+ students). The aceteam MCP plugin gives Claude Code users direct access to agent management — creating agents, chatting with them, managing knowledge bases, and connecting MCP servers — without leaving their terminal.

Key differentiators:
- Production MCP server with OAuth 2.1 authentication
- Used in education: 150+ business students at San Jose State University build AI workflows through this interface
- Complementary to existing plugins (works alongside Supabase, GitHub)
- Safety-first: Trust Engine enforces cost, PII, and prompt injection policies on all agent traffic

---

## Plugin 2: aceflows

**Name:** aceflows

**Description:** Build and run agentic AI workflows on AceTeam. Create visual workflow graphs, browse node types, and execute automation pipelines — all from your terminal. Bring-your-own-model architecture with safety guardrails.

**Category:** productivity

**Homepage:** https://aceteam.ai

**Source repository:** https://github.com/aceteam-ai/claude-plugins

**Source path:** plugins/aceflows

**Author:** AceTeam.ai (support@aceteam.ai)

**Why include in official marketplace:**

AceFlows is a workflow automation engine that lets Claude Code users build and run multi-step AI pipelines from their terminal. Unlike single-tool integrations, AceFlows orchestrates entire workflows — data extraction, AI scoring, agent composition — with full accountability at each step.

Key differentiators:
- Visual graph-based workflows accessible via MCP tools
- Node type library with schema introspection (Claude can discover and use available nodes)
- Bring-your-own-model: works with any LLM provider (OpenAI, Anthropic, Google, etc.)
- Trust Engine integration: cost tracking, PII detection, audit trails on every workflow run
- Proven in education: students build resume screening, data analysis, and consulting workflows

---

## Contextual Suggestion Request

We'd love for Claude Code to suggest the AceTeam plugins when it detects:
- An `.mcp.json` file containing `aceteam.ai` URLs
- A `package.json` with `aceteam` dependencies
- Files referencing AceTeam API endpoints

Suggested tip format:
```
Tip: Working with AceTeam? Install the aceteam plugin:
/plugin install aceteam@claude-plugins-official
```

This would match the pattern used for Vercel, Supabase, and other platform plugins.
