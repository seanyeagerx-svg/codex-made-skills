# Shared Decision Record

Use for every route. Keep this factual and compact; do not expose raw private correspondence.

## Brief

- Goal and decision to make.
- Route, domain, and candidate unit.
- User-confirmed requirements versus suggested assumptions.
- Hard gates, preferences, three to five comparison criteria.
- Scope, intended use, source/access permissions, breadth and shortlist target, effort limit.

## Candidate Ledger

Use a table, JSON, or another locally appropriate structured format. Required fields when applicable:

| Field | Meaning |
| --- | --- |
| id / title / origin | Stable ID, descriptive label, external / supplied / original proposal |
| source / creator / inspected_at | Direct source pointer or supplied record ID; unknown stays unknown |
| work_key / aliases / family | Underlying work, reposts, and grouping; ambiguous matches stay flagged |
| coverage / locator | Discovered, inspected, tested, inaccessible; precise pages, images, states, or video intervals |
| evidence | Short observations plus separately marked reported/proposed/unknown claims |
| gates | Each required condition: pass / fail / unknown, with reason |
| assessment | Per-criterion quality and task fit; feasibility, uncertainty, meaningful disadvantage |
| disposition / reason | Shortlist, reserve, provisional, excluded, duplicate, or unreviewed |
| reuse_status | Inspiration only, terms verified for intended use, or permission unknown |

Do not place credentials, account IDs, raw private chats, or unnecessary personal details in a shareable ledger. Use anonymous participant IDs for need studies. Downloading or including private assets requires the relevant authority; a local ledger does not authorize it.

## Scoring Anchors

Use labels by default, with evidence. Optional scoring:

- 0: observed conflict or material weakness against this criterion.
- 1: partly meets it, with a concrete tradeoff or limitation.
- 2: clearly meets it, supported by relevant observations.
- U: cannot assess from available evidence; not zero and not a midpoint.

Hard gates are separate and cannot be compensated by points. Do not compare totals across different rubrics or normalize missing evidence into a high score. A creator-reported capability may be recorded, but must not be scored as a tested result. Show scoring anchors tailored to the domain before broad evaluation.

Disadvantages must affect this brief and have a stated basis. Do not invent a weakness to fill a table cell. Missing information is a decision-relevant uncertainty, not automatically a defect; for example, absent standing-pose details are not a weakness of a requested seated portrait. If no specific downside is supported, say so and identify only the relevant verification gap.

## User-Facing Shortlist

Use the user's language. Start with a one-sentence conclusion and explicit completion status.

For each finalist show:

1. ID, concise direction name, and actual preview/source. New proposals must say "original proposal".
2. The specific property worth borrowing and why it fits this brief.
3. What must stay unchanged and what can transfer from the reference, when relevant.
4. Main weakness, execution cost, and any evidence gap.
5. A concrete next step, not an unapproved action.

For images, use actual viewed images or lawful source previews when supported; otherwise give direct links and disclose preview limitations. Never invent thumbnails or represent generated mockups as original works. For video, link the work and only the time ranges actually inspected; a poster is not a playable clip. For UI, identify observed screens/states and untested interactions. Needs are shown as concise anonymized evidence cards, not decorative moodboards.

Seven slots can illustrate different useful tradeoffs, but are not a compulsory formula. Do not reserve fixed quotas for "bold", "safe", or "wildcard" choices when the brief excludes them. If style consistency matters, vary execution within that style.

## Audit Footer and Handoff

State sources attempted and relevant source coverage, the work unit, real stage counts, any missed target, and what was not verified. Retain the ledger when a file-based deliverable is requested or needed for a large pool. Local artifact paths should be clickable absolute paths in the response, but not baked into the skill.

Suggested response request: "Choose IDs, tell me what to keep/avoid, or say none and why." Do not require feedback to finish.

After selection, pass only the approved direction, invariants, transferable properties, asset requirements, and evidence limitations to the next production task. Do not describe the handoff as tested production. User approval for a direction is not permission for paid generation or public/client-data uploads.
