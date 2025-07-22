# OpenSteel Design Library

This folder contains all official OpenSteel design variants.

Each design is a downloadable 3D model intended for metal printing and use with a spring-loaded center punch. All variants encode BIP39 seed words using binary marking — no visible letters or numbers are used.

---

## 🔸 Nothaus

**Nothaus** is the first and reference design of the OpenSteel project.

- Shape: Circular
- Diameter: 45 mm
- Capacity: 24 seed words (12 per side)

### Features

- Binary-only layout (each seed word is encoded as a 12-bit pattern)
- Engraved mark on the center of one side to indicate "side A"
- Through hole acts as starting point and optional hanging point
- Slightly concave surface to protect against abrasion
- Requires only a center punch — no engraving, laser, or stamping kits

> A printable visual guide (PDF) will be added soon to help interpret the layout and word positions.

---

## 🧩 How to contribute a design

If you'd like to submit your own OpenSteel-compatible design, follow these steps:

1. Create a folder inside `/designs/` with your design name.
2. Include your `.stl` file(s).
3. Add a `README.md` explaining:
   - Shape and layout
   - Capacity
   - Special features
   - Recommended material and usage

All designs must use binary-based encoding compatible with BIP39 and be fully offline-markable (no digital dependency).

---
