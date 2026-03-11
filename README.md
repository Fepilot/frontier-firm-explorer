# Frontier Firm Explorer

A customer-facing interactive assessment tool that helps organizations discover where they are on the **Frontier Firm** journey — from Foundation (Phase 1) through Expansion (Phase 2) to Frontier (Phase 3).

## What It Does

- **Learn** about the three phases of the Frontier Firm transformation
- **Explore** industry-specific AI scenarios across 10+ industries
- **Assess** your organization across 6 dimensions (Copilot, Agents, Governance, Data, Culture, Leadership)
- **Strategize** with tailored recommendations and next steps
- **Export** a comprehensive PDF report

## 5-Level Phase System

The assessment uses a nuanced 5-level classification with gating rules:

| Phase | Name | Key Criteria |
|-------|------|-------------|
| **1** | Foundation | Early AI journey |
| **1→2** | Foundation → Expansion | Progress but key pillars missing |
| **2** | Expansion | Copilot active + agents piloting |
| **2→3** | Expansion → Frontier | Agents scaling, approaching autonomy |
| **3** | Frontier | Full agent-operated model |

## Tech

Single HTML file — no build step, no dependencies to install. Uses:
- **jsPDF** + **html2canvas** for PDF export (loaded via CDN)
- Pure vanilla JS, CSS, HTML

## Deploy

Drop to any static host. For Vercel:

```bash
vercel --prod
```

## License

Internal Microsoft tool — Frontier Firm Transformation initiative.
