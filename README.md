# Miku's Sengoku History Sanctuary

> *"If you don't know Sengoku history, you can't understand people."* — Miku Nakano (*The Quintessential Quintuplets*)

---

## About the Project

**Miku's Sengoku History Sanctuary** is a custom, multi-file web project built to experiment with and master advanced HTML table structures, semantic layouts, and clean separation of concerns. 

Rather than sticking to generic, uninspired practice exercises, this project was born from a desire to build something entirely personal: a tribute uniting Miku Nakano’s deep-seated fascination with the **Sengoku period** (the Sengoku Jidai) with her uncompromising taste for authentic, character-driven aesthetics.

For all purposes, please consider this project, as it is: a form of fanart made with code and lots of love! Miku is a famous character from *The Quintessential Quintuplets*, and belongs to author Negi Haruba.  I greatly relate to her, so this kind of historical tables makes it even more special!

She deserves all happiness of the world, and everyone should know about how special historical time periods like these can be!

I highly recommend listening to the op music while reading this!

---

## The Motivation & Philosophy

* **Beyond Curriculum Boundaries:** Designed as an independent exploration to push tables, CSS grid alignment, and document structure far beyond what is typically introduced in foundational web development curricula (such as *The Odin Project*).

* **The Sengoku Ethos vs. The Modern World:** The page serves as a thematic contrast. While the modern world is filled with performative noise, half-hearted compromises, and constant hesitation, the Sengoku period was a high-stakes crucible where actions carried ultimate consequences, between the lord and the people around them. Everyone was held accountable. 

* **The Romantic Ideal:** Exploring why legendary busho (warlords) like Takeda Shingen, Sanada Yukimura, and Date Masamune represent the epitome of unyielding conviction, absolute protection, and true masculinity—standing as the ultimate heartthrobs who make you feel completely safe against a chaotic world.

---

## Aesthetic & Design System

Every design choice is intentional, rejecting generic templates in favor of Miku's signature palette:

* **Deep Indigo Background (`#12141c`):** Evokes her signature dark hair and quiet, introspective atmosphere.
* **Soft Matcha-Soda Text (`#d4e6d7`):** Replaces stark white text with a cozy, readable hue inspired by her favorite drink.
* **Warm Cardigan Brown (`#d08770`):** Used for captions, subtitles, and quote borders to match her iconic knitwear.
* **Cyan Headphone Accent (`#88c0d0`):** Integrated via a custom inline SVG vector graphic framing the header with her signature studio headphones, elevating the UX and anchoring her character identity directly into the interface.

---

## File Architecture

Maintained with strict separation of concerns:

```text
Mikutables/
├── index.html        # Semantic HTML5 structure, tables, quotes, and inline SVG branding
└── miku-style.css    # Dedicated CSS stylesheet managing custom properties, dark mode, and grid borders