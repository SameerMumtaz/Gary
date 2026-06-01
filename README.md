[README.md](https://github.com/user-attachments/files/28484936/README.md)
# Gary
DnD Character Sheet
# 🎲 [Your Campaign Name]
### A D&D 5e Campaign Reference Site

A mobile-first web app for tracking characters, sessions, and campaign lore. No frameworks, no installs, no accounts. Just HTML files that work on any phone.

**Live site:** `https://sameermumtaz.github.io/gary/`

---

## 📁 Files

| File | Description |
|------|-------------|
| `index.html` | Party dashboard — main landing page |
| `gary-dicksworth.html` | Gary Dicksworth III's full character sheet |
| `README.md` | This file |
| `SETUP.md` | Detailed GitHub Pages setup instructions |

---

## ⚔️ The Party

| Character | Player | Class | Status |
|-----------|--------|-------|--------|
| Gary Dicksworth III | Sandy | Githyanki Wild Magic Sorcerer | Active |
| *(open slot)* | — | — | Pending |
| *(open slot)* | — | — | Pending |
| *(open slot)* | — | — | Pending |

---

## 🗂️ What's In Each Character Sheet

Every character file is a self-contained single-page app with four tabs:

**⚔ Player Sheet**
- Character identity, appearance, want, fear
- Combat stats — AC, HP, speed, initiative, passive perception
- Ability scores with modifiers
- Full spell list with one-line descriptions
- Key skills with bonuses
- Backstory and traits
- Quick reference bar with every number needed on Day 1

**🎲 DM Companion** *(DM eyes only)*
- Encounter trigger rules
- NPC roster with personalities and signature entrance lines
- d20 social encounter outcome table
- Encounter flow checklist
- Baby mama retirement tracker
- Wild magic surge escalation tracker

**🐉 Arc Guide** *(DM eyes only)*
- Full character arc broken into phases
- Scripted key scenes with exact staging notes
- Relationship dynamics between major NPCs
- Campaign endgame beats

**📝 Dice & Notes**
- Dice roller — d4, d6, d8, d10, d12, d20
- Wild magic surge checker with adjustable threshold
- Baby mama social encounter roller (d20 with auto-interpreted results)
- 🍷 The Tactical Resource flask state roller (Gary-specific)
- Campaign log — structured session entries with location, events, NPCs, loot, next hook
- Personal notes — private freetext scratchpad, auto-saves
- Export / Import JSON — back up or share notes across devices
- Campaign phase tracker and baby mama appearance tracker

---

## 🍷 Gary Dicksworth III — Quick Reference

> *"The cosmos is my oyster. Child support is not my problem."*

| Stat | Value |
|------|-------|
| Race | Githyanki |
| Class | Wild Magic Sorcerer |
| Level | 1 |
| AC | 13 |
| HP | 8 |
| Speed | 30ft |
| Initiative | +3 |
| Spell Attack | +5 |
| Spell Save DC | 13 |
| Passive Perception | 12 |

**Top Skills:** Deception +5 · Persuasion +5 · Intimidation +5 · Arcana +3 · History +3 · Investigation +3

**Active Warrants:** 9 cross-planar summons for child support non-payment. One pursuer is a Red Dragon. One is a Dwarf Cleric whose god is personally involved.

**The Tactical Resource:** A wineskin Gary refers to as a tactical resource. It is not a tactical resource. It is a drinking problem with good branding. Roll d6 at the start of each scene — 1-2 sober (bad), 3-4 liquid courage (dangerous), 5-6 blackout diplomacy (unpredictable).

---

## 📋 Adding a New Character

1. Duplicate `gary-dicksworth.html` → rename to `character-name.html`
2. Change `CHARACTER_KEY` in the script block to match the filename (e.g. `'petra-stormhand'`)
3. Replace all character-specific content throughout the file
4. Add their card to the party grid in `index.html`
5. Upload both files to GitHub — live in 30 seconds

New players can fill out the **Character Builder** tab on the dashboard (`index.html`) — it walks them through every required field and generates a formatted summary to send to the DM.

---

## 💾 Notes & Data

- All notes save to **localStorage** on each player's device
- Notes are **private per device** — use Export/Import JSON to sync with the party
- Export includes campaign log, personal notes, and tracker state
- Importing replaces local data — always export first if you don't want to lose anything
- Deleting browser data or clearing site storage will erase notes — export regularly

---

## 🛠️ Tech Stack

Pure HTML, CSS, and vanilla JavaScript. No build tools, no dependencies, no backend.
Google Fonts loaded from CDN (requires internet for first load — works offline after).
Hosted on GitHub Pages — free, fast, no configuration beyond enabling Pages in repo settings.

---

## 📖 Lore Notes

> *Gary Dicksworth III is a Githyanki Wild Magic Sorcerer operating under a false identity to evade nine active cross-planar child support summons. One of his pursuers is Xal'ixx the Molten, a Red Dragon who is also the mother of Chad — a 10-year-old half-dragon reality-bender who has left home to find his father. Chad is currently traveling alone across the planes. Gary has a locket with Chad's portrait at age 7. Gary calls this "due diligence on a potential business venture." The party knows. They heard Gary say Chad's name in his sleep. No one has mentioned it.*

*The chaos magic always surges hardest when Gary is protecting something he won't admit he loves. It has been surging more frequently lately. Gary blames Moradin. Gary is wrong.*

---

*Built with Claude · Campaign site template available on request*
