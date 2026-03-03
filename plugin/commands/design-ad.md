---
description: Create ad designs in Figma for Meta or Google campaigns.
argument-hint: "[meta|google|both] [brief]"
allowed-tools:
  - Read
  - Write
  - Bash
  - mcp__figma*
---

# /design-ad

## STEP 1: READ SKILL
Read skills/ad-design-guru/SKILL.md completely.

## STEP 2: ASK ALL QUESTIONS
1. Brand name?
2. Figma brand file link?
3. Campaign name?
4. Which Figma page? (list pages, ask which)
5. Formats? (1:1, 4:5, 9:16, 1.91:1, PMax, all)
6. Heading font + weight? Body font? CTA font? (MANDATORY - suggest pairings)
7. Brand colors (hex)? CTA color?
8. Headline text?
9. CTA text?
10. Body copy?
11. Image(s)?

DO NOT CREATE ANYTHING UNTIL ALL ANSWERED.

## STEP 3: BUILD EACH AD

A. Create frame at exact dimensions
B. Add background image filling entire frame
C. Add dark overlay if needed
D. Place EACH element as direct child of the frame.
   DO NOT use auto-layout. DO NOT create wrapper frames.
   Use ABSOLUTE X,Y positioning for each element.
E. All elements MUST be within content zone:
   1:1: x>=145, y>=145, right<=1295, bottom<=1295
   4:5: x>=145, y>=185, right<=1295, bottom<=1615
   9:16: x>=40, y>=250, right<=1040, bottom<=1470
   1.91:1: x>=200, y>=110, right<=1864, bottom<=970

## STEP 4: NAME
Frame: BrandName-MM.DD-Format-Variation (NO spaces)
Layers: CTA, BodyCopy, Heading, Logo, DarkOverlay, Image, Background

## STEP 5: VERIFY
Check every element is inside content zone bounds before showing designer.
