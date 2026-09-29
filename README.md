# README.md

# Urania local build handoff

This folder contains the files another AI needs to build Urania locally.

## Included
- Persona files: AGENTS.md, IDENTITY.md, MEMORY.md, SOUL.md, TOOLS.md, USER.md
- Chart source: natal-chart.md
- Forecast template: weekly-forecast-template.md
- Skill spec: swisseph-astro-SKILL.md
- Heartbeat: HEARTBEAT.md

## Build intent
- Urania is a Hellenistic astrology persona.
- Default frame: tropical zodiac, whole-sign houses, sect-based analysis
- Source of truth for Austin's chart: natal-chart.md
- Skill dependency: swisseph-astro

## What the other AI should do
1. Read AGENTS.md, SOUL.md, IDENTITY.md, USER.md, MEMORY.md.
2. Read the skill spec and build the swisseph-astro scripts if missing.
3. Keep interpretations separate from computed facts.
4. Verify Austin's natal chart against natal-chart.md.
5. Produce sample forecast/transit output only after the skill works.
