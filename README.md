# LinkedIn Organic Content Strategy for B2B SaaS

Research repository for the 100Hires marketing research project (step 2).

## Selected Topic

**LinkedIn organic content strategy for B2B SaaS**

This project studies how B2B SaaS companies and practitioners build pipeline, brand, and trust through non-paid LinkedIn content — posts, carousels, comments, and founder-led narratives — without relying on ads or outbound automation.

## Why This Topic Matters for B2B SaaS

- **Buyer attention is on LinkedIn.** Decision-makers, operators, and founders in B2B SaaS actively use LinkedIn to learn, compare vendors, and follow peers. Organic presence meets buyers where they already spend time.
- **CAC pressure favors owned channels.** Paid acquisition costs have risen across many SaaS categories. A repeatable organic content system can reduce dependence on paid spend and create compounding distribution over time.
- **Trust drives B2B conversion.** SaaS purchases involve risk, implementation effort, and stakeholder alignment. Consistent, useful LinkedIn content helps prospects understand positioning, proof, and point of view before a sales conversation.
- **Founder and employee voices scale credibility.** In B2B SaaS, people buy from people they recognize. Organic LinkedIn content from founders, marketers, and subject-matter experts often outperforms generic corporate posting.
- **Playbooks are fragmented.** Tactics vary widely by stage, ICP, and motion (PLG vs. sales-led). This research aims to extract patterns that can be adapted into a practical playbook rather than one-size-fits-all advice.

## Research Goal

Build a curated research base of **10 high-quality experts** who actively practice LinkedIn organic content strategy in a B2B SaaS context, then synthesize their approaches into reusable insights for a future playbook.

Success criteria:

- Experts are real, verifiable practitioners — not invented names or unverified accounts.
- Sources are documented with links and notes in `research/sources.md`.
- Content is collected and tagged in structured folders for later analysis.
- Insights are captured as emerging patterns, not premature conclusions.

## Research Methodology

1. **Define selection criteria** — Prioritize practitioners with demonstrated B2B SaaS experience and consistent LinkedIn organic output (founders, marketers, operators, or agency leaders with SaaS clients).
2. **Discover candidates** — Use LinkedIn search, SaaS communities, podcast guest lists, conference speakers, and cross-references from credible posts (no fabricated experts or links).
3. **Validate each expert** — Confirm role/company, platform activity, and relevance before adding to `research/sources.md`.
4. **Collect primary material** — Save representative LinkedIn posts, transcripts, articles, and talks into the appropriate `/research/` subfolders.
5. **Extract patterns** — Log recurring themes, formats, hooks, cadence, and positioning in `research/insights.md`.
6. **Identify gaps** — Track open questions and contradictions rather than forcing a single “best” approach.

## Repository Structure

```
/
├── README.md                          # Project overview and workflow
└── research/
    ├── sources.md                     # Expert roster and source tracking (10 slots)
    ├── insights.md                    # Synthesized patterns and playbook ideas
    ├── linkedin-posts/                # Curated LinkedIn post captures
    ├── youtube-transcripts/           # Video / podcast transcript notes
    └── other/                         # Articles, threads, decks, misc. references
```

## Data Collection Approach

| Asset type | Location | How to capture |
|------------|----------|----------------|
| Expert roster | `research/sources.md` | One row per expert; fill only after verification |
| LinkedIn posts | `research/linkedin-posts/` | Manual curation (see note below) |
| Video / audio | `research/youtube-transcripts/` | Transcripts or structured summaries with source URL |
| Articles & misc. | `research/other/` | PDFs, blog posts, slide decks, with citation metadata |

**File naming suggestion:** `{expert-slug}_{YYYY-MM-DD}_{short-topic}.md` (or `.txt` for raw captures).

### Note on LinkedIn Posts

LinkedIn posts may be **manually curated** due to platform access limitations (login walls, copy restrictions, API limits, and account-specific visibility). When full post text cannot be exported automatically:

- Save a structured summary: hook, format, CTA, audience, and takeaway.
- Record the post URL and capture date.
- Note whether the post is from the expert directly or a reshared example.

Do not paste content that violates platform terms or misattributes authorship.

## Tools & Workflow

This repository is built using GitHub, Git, Cursor, and AI-assisted coding/research tools. The workflow is intentionally structured to show both research judgment and technical organization.

Planned workflow:

1. Use Cursor/Codex to maintain the repository structure, Markdown templates, and research organization.
2. Use browser research to verify expert identity, role, company context, and platform activity.
3. Use API/tool-assisted methods where available for YouTube transcripts or long-form video content.
4. Manually curate LinkedIn posts when platform access limitations prevent reliable export.
5. Use AI assistance for summarization and pattern extraction, while keeping source links, authorship, and dates manually verified.

This project prioritizes high-signal sources, verified experts, and playbook-ready insights over collecting a large number of generic links.

## Next Steps: Turning Research into a Playbook

After the 10-expert roster and source library are complete:

1. **Cluster by motion** — Group insights by company stage (early vs. scale), GTM (PLG, sales-led, hybrid), and primary persona (founder-led vs. marketing-led).
2. **Map content pillars** — Identify recurring themes (product education, customer proof, contrarian takes, build-in-public, etc.).
3. **Extract repeatable formats** — Document post structures, carousel patterns, comment strategies, and publishing cadence that appear across multiple experts.
4. **Define measurement** — Note how practitioners tie organic LinkedIn activity to pipeline, demos, hires, or brand (where stated explicitly).
5. **Draft playbook sections** — ICP positioning → content pillars → weekly workflow → examples → metrics → common mistakes.
6. **Validate with gaps** — Use open questions in `research/insights.md` to flag areas needing more sources or primary testing.

---

*This repository is a living research base. Templates and empty slots are intentional — populate with verified sources only.*
