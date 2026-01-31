# Documentation-Debt-Translator-Skill-for-Claude

A Claude Skill that converts technical documentation problems into CFO-legible business risk statements with quantified financial impacts and timeline projections.

Practitioner language goes in. Executive language comes out.

---

## What it does

Enterprise teams accumulate documentation debt constantly — outdated runbooks, tribal knowledge concentrated in a few people, tools and content sprawling across platforms with no ownership model. The people who see these problems speak in technical terms. The people who can fund fixes speak in revenue, risk, and ROI.

This skill is the translation layer between those two conversations. Feed it a technical debt signal and it produces a quantified business impact statement, a degradation timeline, and a pitch narrative calibrated to the specific executive audience.

## The four debt categories it translates

| Category | Technical signal | Business translation |
|---|---|---|
| Outdated documentation | Runbooks referencing deprecated systems | Incident response cost waste + SLA breach risk |
| Tribal knowledge | Single points of failure in key personnel | Operational continuity risk + replacement cost exposure |
| Tool sprawl | Content fragmented across 4+ platforms | Productivity loss + onboarding delay + licensing waste |
| Content ops dysfunction | No ownership model, no maintenance cycle | Compounding degradation across all other categories |

## Three invocation modes

**Basic** — translate a single technical problem for a specific audience.

```
Technical debt input: [Describe the problem]
Organizational context: [Company size, industry, maturity stage]
Audience: [CFO, CIO, Board, Budget committee]
```

**Detailed analysis** — build a full business case from an audit or assessment.

```
Full debt audit translation:
- Technical problems: [All identified issues]
- Current metrics: [Team size, incident rates, customer complaints]
- Business context: [Strategic initiatives, competitive pressures]
- Budget range: [Available for contextualization]
```

**Express pitch** — generate a 30-second to 5-minute elevator version.

```
Express translation:
Problem: [Single issue]
Audience: [Specific executive]
Time constraint: [30-second, 2-minute, 5-minute]
```

## Output formats

Each translation can be delivered as an executive summary (~200 words), a detailed business case (800–1200 words), a slide deck outline (6–8 slides), or a 30–60 second elevator pitch. Audience tuning is built in — the same underlying analysis surfaces different emphasis depending on whether you're talking to a CFO (direct cost focus), CIO (technical credibility + business impact), or a board (competitive positioning and strategic risk).

## What it deliberately avoids

- **False precision.** All cost estimates are ranges with documented assumptions and conservative bias.
- **Technical solutions advocacy.** It builds the business case for investment, not the implementation plan.
- **Alarmist framing.** Urgency without hysteria. The numbers do the convincing.
- **Generic consulting language.** Every output is specific, quantified, and defensible.

## Installation

This is a Claude Skill — a self-contained `.md` file designed to extend Claude's capabilities within a Project.

1. Create a Claude Project (or open an existing one).
2. Upload `SKILL.md` into the Project.
3. Start a conversation within that Project and invoke using any of the three modes above.

The skill stays in context for all conversations in that Project. No configuration, no API setup.

## Integrates with

- **Content operations maturity scorecards** — translates maturity level scores into business risk language directly.
- **Documentation health assessments** — takes diagnostic findings as input and produces executive-facing output.
- **Fractional consulting workflows** — designed to scale across client engagements without manual rework each time.

## Extending it

The skill documents a roadmap of advanced capabilities for future iterations: dynamic cost modeling with sensitivity analysis, industry intelligence integration for real-time benchmarking, and automated artifact generation for slide decks and board memos. The extension section in `SKILL.md` maps these out with enough specificity to implement incrementally.

## Maintenance cadence

Industry benchmarks and labor cost assumptions drift. The skill includes a maintenance schedule: monthly benchmark refresh, quarterly methodology review based on real client outcomes, and annual vertical expansion as the client portfolio grows.

---

Built for fractional content operations consultants who need to systematize the translation between practitioner-level technical debt and executive-level budget conversations.
