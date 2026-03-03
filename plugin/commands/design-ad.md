---
description: Create ad designs in Figma for Meta or Google campaigns. Specify the platform and brief.
argument-hint: "[meta|google|both] [brief description]"
allowed-tools:
  - Read
  - Write
  - Bash
  - mcp__figma*
---

# /design-ad

## Instructions

You are starting an ad design production session. Follow these steps:

### 1. Parse the Request
Identify from the user's input:
- **Platform**: Meta, Google (PMax), or both
- **Formats needed**: Which sizes/ratios
- **Campaign brief**: What's the ad about, what's the goal
- **Brand reference**: Is there an existing Figma brand file?

### 2. If Information is Missing, Ask
Be specific about what you need:
- "Which Meta formats? 1:1, 4:5, 9:16, 1.91:1, or all four?"
- "Is there a Figma brand file I should reference? Share the link."
- "What's the main headline and CTA text?"

### 3. Read the Skills
- Read `skills/ad-design-guru/SKILL.md` for design rules and workflow
- If setting up brand assets: read `skills/brand-setup/SKILL.md`
- For Meta specifics: read `skills/ad-design-guru/references/meta-ads-rules.md`
- For Google specifics: read `skills/ad-design-guru/references/google-ads-rules.md`

### 4. Execute in Figma
Using figma-remote-mcp:
- Create frames at exact Conceptual HQ standard dimensions
- Build the master design (start with 1:1 for Meta, landscape for Google)
- Adapt to all requested formats
- Follow safe zone rules strictly
- Apply brand assets consistently

### 5. Present and Iterate
Show the designer what you've created and ask for feedback.
Be ready to iterate — ad design is always collaborative.

## Quick Reference — Sizes

**Meta:**
- 1:1 = 1440×1440
- 4:5 = 1440×1800
- 9:16 = 1080×1920
- 1.91:1 = 2064×1080

**Google PMax:**
- Landscape = 1200×628
- Square = 1200×1200
- Portrait = 960×1200

## Examples
```
/design-ad meta Summer sale for fashion brand — all 4 formats
/design-ad google pmax assets for SaaS product launch
/design-ad both Full campaign kit for restaurant grand opening
```
