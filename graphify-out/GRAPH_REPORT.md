# Graph Report - ux-writing  (2026-11-23)

## Corpus Check
- 5 files · ~4,505 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 61 nodes · 58 edges · 9 communities (7 shown, 2 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `4e547bca`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- UX Writing Audit
- UX Microcopy Audit
- Rules
- Features
- Context-specific rules
- References
- Framework-specific scanning guide
- CLAUDE.md
- .claude/CLAUDE.md

## God Nodes (most connected - your core abstractions)
1. `UX Microcopy Audit` - 15 edges
2. `Rules` - 9 edges
3. `UX Writing Audit` - 8 edges
4. `Features` - 7 edges
5. `Context-specific rules` - 7 edges
6. `Framework-specific scanning guide` - 6 edges
7. `References` - 6 edges
8. `Quick start` - 3 edges
9. `graphify` - 1 edges
10. `graphify` - 1 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Communities (9 total, 2 thin omitted)

### Community 0 - "UX Writing Audit"
Cohesion: 0.18
Nodes (9): Example findings, Install, License, Quick start, References, Severity scoring, Use, UX Writing Audit (+1 more)

### Community 1 - "UX Microcopy Audit"
Cohesion: 0.18
Nodes (11): Audit categories by priority, Brand voice profile, Common anti-patterns, Cross-skill integration, How to use, Output format, Review summary, Severity scoring rubric (+3 more)

### Community 2 - "Rules"
Cohesion: 0.22
Nodes (9): 1. Clarity and scannability (critical), 2. Actionable language (critical), 3. Error and validation messages (critical), 4. Tone and voice consistency (high), 5. Inclusivity and accessibility (high), 6. Empty and loading states (medium), 7. Redundancy and filler (medium), 8. Localization readiness (low) (+1 more)

### Community 3 - "Features"
Cohesion: 0.29
Nodes (7): 20 common anti-patterns, Before/after examples, Brand voice profile, Context-specific rules, Cross-skill integration, Features, Framework-specific scanning

### Community 4 - "Context-specific rules"
Cohesion: 0.29
Nodes (7): Context-specific rules, Destructive and irreversible actions, Error states and recovery, Notifications and toasts, Onboarding and first-run, Settings and configuration, Transactional (payments, account changes)

### Community 5 - "References"
Cohesion: 0.33
Nodes (6): Accessibility and inclusivity, Books, Design system writing guides, Foundational UX writing, Localization, References

### Community 6 - "Framework-specific scanning guide"
Cohesion: 0.33
Nodes (6): Framework-specific scanning guide, HTML (static), Next.js / React (JSX/TSX), React Native, Svelte, Vue (SFC)

## Knowledge Gaps
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `UX Microcopy Audit` connect `UX Microcopy Audit` to `UX Writing Audit`, `Rules`, `Context-specific rules`, `References`, `Framework-specific scanning guide`?**
  _High betweenness centrality (0.734) - this node is a cross-community bridge._
- **Why does `UX Writing Audit` connect `UX Writing Audit` to `Features`?**
  _High betweenness centrality (0.393) - this node is a cross-community bridge._
- **Why does `Rules` connect `Rules` to `UX Microcopy Audit`?**
  _High betweenness centrality (0.233) - this node is a cross-community bridge._