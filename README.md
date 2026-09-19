# HalfOpen: Black ICE

A hidden-information deduction game for iPhone and iPad.

A *half-open scan* is a real reconnaissance technique — probe a port, read the reply,
withdraw before the connection completes. That is the game in one phrase.

You run a sector. You defend it by placing **ICE** — Intrusion Countermeasures
Electronics — and you probe the opposing sector to find and break theirs before they
break yours.

## 

- **ICE nodes are polyominoes, not straight lines.** Finding one occupied cell no
  longer narrows the search to four neighbours, so deduction becomes two-dimensional.
  Each silhouette is distinct enough that partial information tells you *which* node
  you have found, and therefore what is still out there.
- **No two nodes may sit edge to edge.** Breaking one hands you a provably clear
  border, and nothing can hide by hugging something else into an ambiguous blob.
- **A turn is a budget, not a shot.** Three cycles, spent on a precise single-cell
  probe or on a wider one that returns only a count — never which cells.
- **Losing ground buys you time.** Every node of yours that breaks grants you a cycle
  back on your next turn.

The result is a game where you spend most of your attention on what you have *ruled
out*, and where a reading that resolves nothing today can be forced by a single probe
three turns later.

## Look

Terminal green and amber on near-black. Monospaced throughout, scanlines you have to
look for, and phosphor only on what is live.

## Status

In development, targeting iOS 27. Not yet released.

---

© 2026 illitrate Publicashions. All rights reserved.
