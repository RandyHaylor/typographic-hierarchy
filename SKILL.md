---
name: typographic-hierarchy
description: "Structure all documentation, notes, and text output using typographic hierarchy principles. Information is organized into visual levels so content is consumable at multiple reading distances — from a quick scan to a deep read. Use when creating docs, research notes, summaries, READMEs, or any structured text output."
---

# Typographic Hierarchy

## When to Use This Skill

Use this skill when creating or formatting:
- Documentation, research notes, summaries
- READMEs, project overviews, technical specs
- Any text file where a reader needs to extract value at different levels of attention
- When the user requests "scannable," "concise," or "well-structured" output

## Core Concept

Information is structured into **levels of entry** — each level is readable independently and provides value without requiring the reader to go deeper.

Think: concert poster. Each level pulls the reader one step closer.

## The Levels

### H1 — The What (across the street)
- A reader who sees only H1s knows what topics exist.
- H1 is the domain — it contains multiple H2 subjects beneath it.

### H2 — The Map (12 feet away)
- Well-named divisions that, when scanned alone, give a complete overview of the subject.
- Like SOLID variable names — the label itself teaches.
- Multiple H2s per H1. A single H2 under an H1 means one of them is redundant.

### H3 — The Takeaway (arm's length)
- A reader who scans H2s and H3s walks away with the key insights without reading a single bullet.
- Multiple H3s per H2. Each is a distinct insight or conclusion within that subject.

### Bullets — The Facts (reading)
- Concise but complete — a bullet holds a whole thought, not a fragment of one.

### Nested Bullets — The Proof (studying)
- Stats, citations, exceptions backing the parent bullet.
- Only exists when a bullet needs supporting evidence.

### External Concepts — Don't Redefine
- If it's a standard concept, one bullet describing the high level + a link. No textbook rewrites.

## Rules

### 1. Every Level Stands Alone
Each level must deliver value independently. A reader who only scans H1+H2 should walk away informed. A reader who only reads bullets under one H3 should get the full detail for that subtopic.

### 2. No Prose Paragraphs
Never write a wall of text. If a thought has multiple parts, break it into bullets. But don't split bullets for the sake of it — a bullet holds a whole thought.

### 3. Front-Load Meaning
The first words of every heading and bullet carry the point. Don't bury the lead.

```
WRONG: "One of the things we discovered during research is that policy contradictions are common"
RIGHT: "Policy contradictions are routine — research confirms they're inevitable at scale"
```

### 4. Concise Over Complete
Cut every word that doesn't add information. Prefer fragments over sentences when meaning is preserved.

```
WRONG: "It is important to note that there are approximately 69% of organizations that find regulations too complex"
RIGHT: "69% of organizations find regulations too complex or too numerous"
```

### 5. Nest Only When Necessary
A bullet gets sub-bullets only when it has genuine child details. Don't nest for the sake of nesting. Two levels of bullets is the typical max. Three is the hard limit.

### 6. Consistent Formatting
- H1: ALL CAPS or title case — one per document or per major topic
- H2: Title Case — structural sections
- H3: Title Case or sentence case — insight-level headers
- Bullets: sentence fragment or short sentence, no trailing periods unless full sentences
- Nested bullets: same rules, indented one level

## Example

```
YARD MAINTENANCE
================

Raking Leaves
-------------
### Neglected leaves kill turf and harbor pests

- A thick leaf layer blocks sunlight and traps moisture, causing rot within weeks
- Wet piles harbor ticks, mold, and fungal disease
  - Lyme disease risk increases in yards with persistent leaf litter (CDC)

### Match tool to yard size, not price tag

- Under 1/4 acre — a 30" fan rake is all you need
- Over 1/4 acre — leaf blower saves hours; corded is fine near outlets
- Tarps beat bags every time for hauling to the curb

### Rake downwind toward one collection point

- Check wind direction before starting — let it do half the work
- Mow over thin layers instead of raking — mulched leaves feed the lawn
  - Mulching returns nitrogen to soil (https://en.wikipedia.org/wiki/Mulch)

Mowing Strategy
---------------
### Mow height matters more than mower quality

- Cool-season grass: 3-4 inches, never cut more than 1/3 of blade height
- Taller grass shades roots, retains moisture, crowds out weeds

### Dull blades tear grass and invite disease

- Sharpen every 20-25 hours of use
- Torn tips turn brown within days and become entry points for fungal infection
```

## Anti-Patterns

### Wall of Text
Dense paragraphs where the reader must process everything to find anything. No entry points. No scan path.

### Flat Bullet Dumps
Long undifferentiated lists with no headers or grouping. Reader can't tell what's important or how items relate.

### Over-Nesting
Four+ levels of indentation. Reader loses context of what parent they're under. Signals the content needs restructuring, not deeper nesting.

### Decorative Headers
Headers that don't carry information: "Introduction," "Background," "Discussion." Use headers that state the insight: "Policy contradictions are routine and pervasive."
