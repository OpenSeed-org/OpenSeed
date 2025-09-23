# Nothaus12x12 Design

**Nothaus12x12** is the first reference design of the OpenSeed project.

It is a compact, circular plate intended for durable backup of a 12- or 24-word BIP39 seed phrase.  
The design encodes words in **binary** using a spring-loaded center punch.

---

## 🔧 Specifications

- **Shape:** Circular
- **Diameter:** 38 mm
- **Capacity:** 24 seed words (12 per side)
- **Bits per row:** 12 (enough to represent all 2048 words in the BIP39 list)
- **Lines per side:** 12 curved rows
- **Markings:**
  - Central engraved mark on one side to indicate "Side A"
  - Shallow central hole for orientation.
- **Surface:** Slightly concave to reduce abrasion and protect against wear

---

## 📐 Options for use with a 12-word seedphrase

- For maximum redundancy, both sides of the plate can be engraved with the same 12-word seed.
- Alternatively, you can engrave two different 12-word passphrases, one on each side.
- In case of an irreversible error on one side while engraving the plate, the plate can still be used with the remaining side.
- For a more compact option (at the expense of redundancy), we have the Nothaus6x6, with a 30 mm diameter design that fits 6 words per side (12 words total).

---

## 📐 Options for use with a 24-word seedphrase

- Use **Side A** for words 1–12 and **Side B** for words 13–24, the central engraved mark indicates which side is **Side A**.
- In the case of an irreversible error on one of the sides, the plate will be unusable for a 24-word password. If you prefer a plate with greater redundancy, we have the Nothaus24x24, with a 50 mm diameter design that fits 24 words per side (48 words in total).

> A printable PDF guide will be provided to illustrate the orientation and binary layout.

---

## ⚙️ Recommended printing

- **Material:** Stainless Steel 316L or Titanium
- **Finish:** Raw metal (no polish required)  
- **Method:** 3D metal printing via services such as JLC3DP, Craftcloud, or Shapeways

---

## 🛠️ Usage

1. [Download the STL file](./nothaus12x12-v1.stl)
2. Print in stainless steel via a 3D printing service
3. Use a spring-loaded center punch to mark each bit according to your BIP39 seed
4. Store securely in a safe place, away from cameras and digital devices

---

## 🧩 Contribution

This design is part of the OpenSeed project. Community contributions are welcome.  
If you create a variation, please include:
- Your `.stl` file
- A `README.md` describing the layout and specs
- Optional diagrams or guides

---
