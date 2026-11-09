# Labeling Guidelines — Boots vs Sneakers

## Overview

These guidelines define the rules for classifying footwear images into two mutually exclusive categories: **Boots** and **Sneakers**.

---

## Categories

### Boots
Label an image as `Boots` if the footwear:
- Covers the ankle or extends above it
- Includes Chelsea boots, ankle boots, knee-high boots, combat boots, or rain boots

### Sneakers
Label an image as `Sneakers` if the footwear:
- Does not cover the ankle
- Is designed primarily for casual wear, sport, or athletic use
- Includes running shoes, basketball shoes, low-top trainers, and canvas sneakers

---

## Edge Cases

| Scenario | Label | Reason |
|---|---|---|
| High-top sneaker covering the ankle | Sneakers | Athletic design intent overrides height |
| Short ankle boot with sneaker sole | Boots | Ankle coverage is the primary criterion |
| Image is blurry or ambiguous | Skip / flag | Do not guess; mark for review |

---

## General Rules

- Apply labels based on the footwear's primary visible features.
- When in doubt, flag the image for a second review rather than guessing.
- Do not consider color, brand, or price — only shape and coverage.
