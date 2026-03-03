---
description: Set up a brand asset file in Figma for a new or existing client. Organizes colors, fonts, logos, and style references.
argument-hint: "[client name]"
allowed-tools:
  - Read
  - Write
  - Bash
  - mcp__figma*
---

# /setup-brand

## Instructions

You are setting up a brand asset file in Figma for ad production.

### 1. Read the brand-setup skill
Read `skills/brand-setup/SKILL.md` for the complete workflow and file structure.

### 2. Ask What's Available
- "Do you have a brand book or style guide?"
- "Is there an existing Figma file with brand assets?"
- "Can you share the client's website URL?"
- "Do you have logo files?"

### 3. Create the Brand Assets Structure in Figma
Using figma-remote-mcp, build the standardized brand page:
- Color palette with hex values
- Typography scale
- Logo variations
- Imagery style reference

### 4. Confirm with the Designer
Present the brand setup and ask for approval before ad production begins.

## Examples
```
/setup-brand Acme Coffee Co
/setup-brand new client — website is example.com
```
