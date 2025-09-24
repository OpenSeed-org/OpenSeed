# OpenSteel Design Library

This folder contains all official OpenSteel design variants.

Each design is a downloadable 3D model intended for metal printing and use with a spring-loaded center punch. All variants encode BIP39 seed words using binary marking — no visible letters or numbers are used.

---

## 📊 Nothaus Design Comparison

| Design           | Diameter | Words per Side | Total Capacity | Best for | Link |
|------------------|----------|----------------|----------------|----------|------|
| **Nothaus6x6**   | 30 mm    | 6              | 12             | Maximum portability and discretion | [View](./nothaus6x6) |
| **Nothaus12x12** | 38 mm    | 12             | 24             | Standard backups for 12 or 24-word seeds | [View](./nothaus12x12) |
| **Nothaus24x24** | 50 mm    | 24             | 48             | High redundancy for 24-word seeds | [View](./nothaus24x24) |

### Features

- Binary-only layout (each seed word is encoded as a 12-bit binary pattern)
- Engraved mark on the center of one side to indicate "side A"
- Through hole acts as starting point reference
- Slightly concave surface to protect against wear
- Optional hanging point on the side
- Requires only an automatic center punch — no engraving, laser, or stamping kits

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
