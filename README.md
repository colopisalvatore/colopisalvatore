# Salvatore Colopi

I modernize legacy software without stopping production.

Tech lead on a multi-tenant restaurant SaaS. I build by orchestrating AI agents
(Claude Code, MCP): I own the architecture, set the guardrails and verify what ships.

**What that looks like**

- **Legacy to modern:** strangler-fig migration from a legacy PHP system to a Laravel 12 API
  with a React frontend, behind a gateway that diffs old vs new on real traffic.
- **Security in the code:** systematic IDOR audit, one fail-closed tenant guard,
  architecture tests that fail CI, SSRF protection, rate limiting.
- **Infrastructure and delivery:** from manual FTP deploys to PRs, scoped tests,
  per-part deploys and release trains. Redis/Horizon queues, DB black-box recorder, status page.
- **AI and automation:** marketing automation in production, a company brain on Manent,
  agent rules enforced by CI.

## Open source

- **[Manent](https://github.com/colopisalvatore/manent)**: file-first, git-versioned memory
  for AI agents. Markdown vault + MCP server, eval harness, audience-filtered views.
- **[Glasshopper](https://github.com/colopisalvatore/glasshopper)**: React dashboards for
  Home Assistant as native sidebar panels. Installable via HACS.
- **[yt_learner](https://github.com/colopisalvatore/yt-learner-claude-plugin)**: Claude Code
  plugin + Python CLI that turns a YouTube tutorial into an executable skill and a knowledge card.

## Stack

React · Next.js · TypeScript · Laravel · PHP · Flutter · Vue · Python/FastAPI · PostgreSQL · Redis ·
Docker · GitHub Actions · MCP

## Elsewhere

[salvatorecolopi.com](https://salvatorecolopi.com) · [LinkedIn](https://linkedin.com/in/salvatore-colopi)
