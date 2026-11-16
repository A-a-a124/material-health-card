# Material Health Card

**Every warehouse knows what it holds. This one also knows how much life each part has left.**

**Live demo:** https://a-a-a124.github.io/material-health-card/

A one-page concept prototype for a materials warehouse that stores spare parts for its clients. A shelf-life date assumes ideal storage, but a seal that spent eight months in an open yard at 37°C has aged far faster than its calendar age says. The card shows both ages side by side and turns that into a clear decision.

## What it does
- **Calendar age vs real age** for each part, from where it was stored and for how long.
- **Storage history:** every place the part stayed and how many times faster it aged there.
- **Care record:** preservation tasks, with overdue ones flagged.
- **Verdict stamp:** Fit to issue, Care needed or Hold.
- **Outlook and look-ahead:** when the part reaches the end of its shelf life, how much longer it would last in the air-conditioned store, and its state months from now.
- **Real exports:** a one-page A4 PDF handover certificate and an Excel register (4 sheets), both built in the browser.

## How to run
Open `index.html` in any modern browser. It is a single file and runs fully offline: no install, no server, no data leaves the computer.

## Important
All parts, locations, clients and figures are **sample data** for a concept demonstration. Real age is a simplified estimate (every 10°C above 25°C speeds ageing by a set factor per material type, with allowances for humidity and sunlight); in practice engineers would set these values per material.

Designed by Abdullah Aladhyani.
