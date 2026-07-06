# damo-plugins

A personal [Claude Code](https://claude.com/claude-code) plugin marketplace.

## Plugins

### deck-review

Generates and reviews investor pitch decks using Vinod Khosla's storytelling-first methodology - headlines-first drafting, the 5-second test, one message per slide, fear/greed framing, defanging risks, and the appendix strategy.

Two modes:

- **Generate** - interviews you for the essentials, drafts the headline story first (the headlines alone must sell), then produces full slide-by-slide content, a 30-second commercial, and an appendix skeleton of hard questions.
- **Review** - runs every slide through the 5-second test, grades the narrative arc and cognitive load, and shows the exact rewrite for each failing slide - not just the critique.

## Installation

In Claude Code, run:

```
/plugin marketplace add DamoDoesGH/claude-plugins
/plugin install deck-review@damo-plugins
```

Then ask Claude things like:

- "Use the deck-review agent to review ~/Desktop/seed-deck.pdf"
- "Have deck-review draft a Series A deck for my company"

## Credits

Methodology distilled from Vinod Khosla's talk on how to present to VCs.
