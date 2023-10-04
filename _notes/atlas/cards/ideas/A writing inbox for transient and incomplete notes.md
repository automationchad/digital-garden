---
up:
  - "[[Home]]"
related:
  - "[[A reading inbox to capture possibly-useful references]]"
created: 2023-09-29
tags:
  - 0🌲
---

``` dataview
TABLE WITHOUT ID
 file.link as "Encounters and new notes",
 (date(today) - file.cday).day as "Days alive"

FROM "encounters" 

SORT file.cday asc

LIMIT 20
```

Even if you aspire to write [[Evergreen notes]], most notes begin as transient notes. You should be able to capture thoughts without friction ([[Close open loops]]), then reliably develop them into evergreen notes over time ([[Knowledge work should accrete]]). This implies two important mechanisms:

1. a quick way to capture transient notes which clearly isolates them from evergreen notes; and
2. a place to put notes you want to develop further and a practice which reliably drains it ([[Inboxes only work if you trust how they’re drained]])

I use a “writing inbox” for this purpose. Undeveloped ideas, excerpts from my [[Daily working log]], notes from reading, one-line prompts, etc all begin in that queue. During [[My morning writing practice]], I’ll look through notes in this inbox and spend time developing any that strike me. On most days, I spend the majority of my writing time in this way.

Many notes in my writing inbox end up as evergreen notes, but that’s not appropriate (or possible) for all of them. If a note doesn’t seem sufficiently interesting after a few looks, it’s best to archive or delete it. (A challenge here: [[Triage strategies for maintaining inboxes (e.g. Inbox Zero) are often too brittle]])

While I’m at my computer, I capture notes directly into my writing inbox. I also feed it with: [[Pocket memo pad to capture into writing inbox while out]].