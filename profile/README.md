# Lookout

Vercel Web Analytics for every project, in one view.

Lookout reads the analytics Vercel already collects and puts all your projects on one board:
visitors, page views, pages per visit, Core Web Vitals and conversions, side by side.

- **Scorecard**: a grade from A to D for each landing page.
- **Fix list**: what to fix first on each board, ranked by visitors affected.
- **Flow**: which of your sites send visitors to which.
- **Share links**: read-only boards for clients, with no Vercel seat.
- **Alerts**: email and push when a site drops or spikes.
- **API and MCP**: ask about your analytics from Claude, Cursor or your own code.

**[lookoutstats.com](https://lookoutstats.com)** · [Live demo](https://lookoutstats.com/demo) · [Changelog](https://lookoutstats.com/changelog)

## Open source

- [lookout-mcp](https://github.com/lookoutstats/lookout-mcp): the MCP server for Lookout (MIT).
- [lookout-skills](https://github.com/lookoutstats/lookout-skills): agent skills for Claude Code, Cursor, Codex and other agents (MIT). `lookout-fix` fixes the top item of your Fix list in your code. `lookout-report` writes a weekly report from your boards.

  ```text
  /plugin marketplace add lookoutstats/lookout-skills    # Claude Code
  npx skills add lookoutstats/lookout-skills             # Cursor, Codex, Copilot and others
  ```

Lookout is not affiliated with Vercel Inc. Contact: hello@lookoutstats.com
