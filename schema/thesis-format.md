# Thesis Frontmatter Schema

Every thesis markdown file must have this YAML frontmatter:

```yaml
---
slug: thesis-slug              # URL-safe identifier
title: "Thesis Title"          # Display title
status: active                 # active | evolving | challenged | archived
version: "2.4"                 # Semantic version
created: 2024-08-01            # ISO date
updated: 2024-12-27            # ISO date, updated on each publish
connections:                   # Related thesis slugs
  - other-thesis
  - another-thesis
signal_balance:                # Current signal counts
  supporting: 12
  challenging: 3
  evolving: 5
---
```

## Status Values

- **active**: Thesis has strong supporting evidence
- **evolving**: Thesis is being refined based on new signals
- **challenged**: Significant challenging signals need addressing
- **archived**: Thesis retired or merged into another

## Content Structure

After frontmatter, thesis content should include:

1. **Core Argument** - One paragraph summary
2. **Key Claims** - Numbered, testable claims
3. **Evidence** - Supporting signals and data
4. **Challenges** - Known counter-arguments
5. **Connections** - How this links to other theses
