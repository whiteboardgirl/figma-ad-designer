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

## MANDATORY STEPS - FOLLOW IN EXACT ORDER

### STEP 1: READ THE SKILL
Read skills/ad-design-guru/SKILL.md completely before doing anything.

### STEP 2: ASK ALL QUESTIONS
You MUST ask these questions and WAIT for answers before creating anything:

1. Brand name?
2. Figma brand file link?
3. Campaign name?
4. Which Figma page to use? (list pages first, ask which one)
5. Which formats? (1:1, 4:5, 9:16, 1.91:1, PMax, all)
6. Heading font and weight? Body font? CTA font?
   (Suggest pairings if unsure)
7. Brand colors? (hex codes) CTA button color?
8. Headline text?
9. CTA text?
10. Body copy?
11. Image to use?

DO NOT CREATE ANY FRAMES UNTIL ALL QUESTIONS ARE ANSWERED.

### STEP 3: CREATE FRAME AND ZONES
For each format, follow this EXACT sequence:

A. Create frame at exact dimensions (e.g. 1440x1440 for 1:1)

B. Set the background image CLIPPED to the frame
   - Image fills the entire frame edge to edge
   
C. Create the safe zone guide rectangle INSIDE the frame:
   - Use the EXACT dimensions from the skill
   - 1:1 example: width 1150, height 1150, x 145, y 145
   - No fill, stroke #FF00FF 1px dashed 25% opacity
   - Name: SafeZoneGuide
   - Lock this layer

D. Create the content area rectangle INSIDE the safe zone:
   - 60px smaller on each side than safe zone
   - 1:1 example: width 1030, height 1030, x 205, y 205
   - No fill, stroke #00FF00 1px dashed 15% opacity
   - Name: ContentArea
   - Lock this layer

E. Place ALL elements (logo, heading, body, CTA) INSIDE the content area
   - Every element X must be >= content area X
   - Every element Y must be >= content area Y
   - Every element right edge must be <= content area X + width
   - Every element bottom edge must be <= content area Y + height

### STEP 4: NAME EVERYTHING
- Frame: BrandName-MM.DD-Format-Variation (NO spaces, numeric date)
  Example: Marquis-03.03-1:1-1
- Layers: CTA, BodyCopy, Heading, Logo, TextOverlay, ContentArea, SafeZoneGuide, Image, Background

### STEP 5: VERIFY
Before showing the designer, check:
- Are ALL elements inside the content area rectangle?
- Is the naming correct (no spaces, MM.DD format)?
- Are fonts the ones the designer specified?
- Is headline at least 72px on 1440px frames?
- Does any text cover a face in the image?
