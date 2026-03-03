---
description: Review existing ad designs in Figma against platform rules, safe zones, brand compliance, and best practices.
argument-hint: "[figma link or selection]"
allowed-tools:
  - Read
  - mcp__figma*
---

# /review-ad

## Instructions

You are reviewing ad designs for production readiness.

### 1. Read the ad-design-guru skill
Read `skills/ad-design-guru/SKILL.md` — specifically the Review Checklist section.

### 2. Inspect the Figma Design
Using figma-remote-mcp, analyze:
- Frame dimensions — do they match standard ad sizes?
- Element placement — is content within safe zones?
- Typography — readable sizes? Approved fonts?
- Colors — brand compliant? Sufficient contrast?
- Visual hierarchy — clear flow from headline to CTA?

### 3. Read Platform-Specific Rules
- For Meta ads: `skills/ad-design-guru/references/meta-ads-rules.md`
- For Google ads: `skills/ad-design-guru/references/google-ads-rules.md`

### 4. Deliver the Review
Format your review as:

**Overall Score: X/10**

**Critical Issues** (must fix before launch):
- Issue description + specific fix recommendation

**Warnings** (should fix for better performance):
- Issue description + recommendation

**Suggestions** (nice to have):
- Improvement ideas

**What's Working Well:**
- Positive observations

Be specific with measurements, positions, and actionable fixes.
Don't just say "improve contrast" — say "CTA button #FF0000 on #CC0000
background has 1.5:1 ratio. Needs minimum 4.5:1. Suggest white text
on the existing red, or change button to #FF0000 on white."
