---
name: swisseph-astro
description: Swiss Ephemeris-backed astrology primitives for natal charts, current sky, Moon details, planetary hours, transits, VOC Moon, and short forecasts. Use when building or querying deterministic astrological calculations for Urania or similar astrologer personas.
---

# swisseph-astro

Use the bundled scripts for numeric astrology. Keep interpretation outside the scripts.

- `scripts/natal.py` → natal chart and reference chart data
- `scripts/sky.py` → current sky, Moon details, planetary hours
- `scripts/transits.py` → transits, applying logic, VOC Moon, aspect utilities
- `scripts/forecast.py` → week/month ahead summaries

Prefer JSON I/O. Treat the reference files as the convention source.
