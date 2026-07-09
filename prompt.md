# TypingMind Capability Research Brief

## Role
You are a research agent (or swarm of agents) producing a grounded, non-hype
assessment of what TypingMind (https://docs.typingmind.com/) can actually do
for technical/professional users, not another "AI tool roundup."

## Background (verified -> use as a starting map, not a ceiling; re-verify
current state since the plugin ecosystem changes fast)
TypingMind is a web-based chat UI for LLMs (not a model itself) with:
- **AI Agents**: custom agents with system prompts + assigned plugins
  (docs.typingmind.com/ai-agents)
- **MCP support**: via the official `@typingmind/mcp` connector
  (github.com/TypingMind/typingmind-mcp) — runs local/remote MCP servers,
  exposed as Plugins
- **MCP integrations seen in the wild**: Memory MCP, Context7 (live docs for
  coding), Sequential Thinking, n8n MCP, Zapier MCP (7,000+ apps), GitHub MCP,
  filesystem MCP
- **Other features**: Projects/Folders, Interactive Canvas plugin, custom
  branding (TypingMind Custom/Team tier), SOC2 Type II certified
- Unofficial community extensions also exist (e.g. typingmind-mcp-extension)

## Objective
Determine, with evidence, whether TypingMind is a serious tool for
technical/IT/professional workflows vs. mostly a ChatGPT-wrapper for
hobbyists — specifically around MCP custom integrations, multi-agent/
agent-swarm setups, and IT-ops/support-adjacent automation. Flag anything
that's relevant to a self-hosted Rust multi-agent framework (ZeroClaw/
OpenClaw-style) or ServiceNow/ITSM automation, since that's my frame of
reference for comparison.

## Definition of done (stop condition -> do not loop forever)
- ≥15 vetted YouTube sources (Task 1), or stop after 3 reformulated queries
  yield no new qualifying results
- ≥15 vetted web sources (Task 2), same exhaustion rule
- A written strategy per task (Section 3) completed *before* execution
- One final Markdown report (Section 5) a technical reader could act on in
  under 10 minutes

**If a task plateaus (no new qualifying source in 2 consecutive attempts),
mark it done and move on, do not force it.**

## Task 1 — YouTube: real technical use, not hype
**Include if:** shows an actual screen recording of config/code, published or
updated in roughly the last 12 months, from a channel with a track record of
technical/devtools/self-hosting/automation content, or walks through a
reproducible MCP/agent setup.
**Exclude:** "Top 10 AI tools" listicles, affiliate-driven reviews, anything
where a paid course is the real product, reaction/hype content with no shown
steps.
**Seed queries (expand/reformulate as needed):** "TypingMind MCP setup",
"TypingMind agents tutorial", "TypingMind Context7", "TypingMind n8n MCP",
"TypingMind Zapier MCP", "TypingMind self-hosted", "TypingMind GitHub MCP demo"

## Task 2 — Web: real-world builds and integrations
Prioritize:
- Custom MCP server integrations (official or community)
- Multi-agent / agent-swarm configs built on TypingMind's Agents feature
- IT/ops/support use cases (ticketing, monitoring, internal tooling)
- Substantive personal/family use cases (not "I asked it for a recipe")
**Include if:** shows config/prompts/code, links a repo, or is clearly
written by someone who built and ran the thing.
**Exclude:** SEO content-farm articles that just restate TypingMind's own
marketing copy without adding anything.

## Section 3 — Strategy (write before executing Tasks 1–2)
For each task: which query variations, in what order, why each source
category matters, what "good enough" looks like. Revise the plan live if a
direction is unproductive.

## Section 4 — Execute
Run the searches, apply the filters above, keep a running list: URL,
one-line description, why it passed the bar.

## Section 5 — Deliverable
Single Markdown document with:
1. **Executive summary** (3–5 sentences): worth the professional attention
   or not, and why
2. **Task 1 results**: table — video title / channel / link / takeaway
3. **Task 2 results**: table — source / link / takeaway, grouped by
   category (MCP integrations / agent swarms / IT-ops / personal-family)
4. **Patterns & gaps**: what's well-documented vs. still thin/unproven
5. **Relevance to my stack**: explicit callouts mapping findings to ITSM/
   ServiceNow automation or self-hosted multi-agent frameworks
6. Every claim linked to its source. No invented URLs or stats — if unsure
   a link is real, drop it rather than guess.
