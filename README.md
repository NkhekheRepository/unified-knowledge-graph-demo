# Public Demo — Unified Knowledge Graph (Signal Stewardship)

> **PUBLIC DEMO** — sanitized. Real project data, sources, runtime, URLs, and evidence state are not exposed.

## What it is
An interactive, offline web app that visualizes a **unified knowledge fabric** as entities and typed relationships: spines (governance↔curation), libraries, bridges, timeline, synapse overlays, presence, runtime, and state — for *Signal Stewardship for a Living Commons*.

## Open
Open `index.html` in any browser (works offline; no backend).

## Demo limits
- No private channel/playlist URLs, evidence-loop heads, tracks/gaps, or local runtime details.
- No data exfiltration: static, embedded, local files only.
- For improvement, start from the private project in the main workspace.

## Tech
HTML + vanilla JS + bundled `lib/vis-network.min.js` (no CDN). `data/graph.js` is the editable demo graph.

## Explore
Search, filters, Layers, quick jumps, hover highlight, 1/2-hop focus, SYN/TEN/POT/LOOP overlays, index navigation, relationship details, `Export JSON`.
