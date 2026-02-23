# RimWorld Twitch Commands

This is the command reference for the **MizunaTwitch** RimWorld mod.
Type any of these commands in Twitch chat while the stream is live.

---

## Getting Started

Before using any other command, you need to **join the colony first**.

| Command | Description |
|---------|-------------|
| `!join` | Spawn your colonist with a random gender. |
| `!join m` | Spawn your colonist as **male**. |
| `!join f` | Spawn your colonist as **female**. |
| `!help` | Show the quick command summary in chat. |

---

## Colonist Info

| Command | Description |
|---------|-------------|
| `!stats` | Show your **EXP** and current **Skill Level** (points currency). |
| `!skills` | List your colonist's RimWorld skills and their current levels. |
| `!mood` | Check your colonist's current mood percentage and label (e.g. *Content*, *Stressed*, *About to break*). |

---

## Skill Upgrades

Each time you level up (by earning EXP through watching/chatting), you get **Skill Level points** to spend.

| Command | Description |
|---------|-------------|
| `!skills [skill] [n]` | Spend **n** Skill Level points to raise the named skill by **n** levels. Example: `!skills shooting 2` |

**Notes:**
- Use `!skills` first to see what skills your colonist has.
- You cannot upgrade a skill your colonist has no passion for.
- Skills max out at level 20.

---

## Work Management

Control what jobs your colonist prioritizes in the colony.

| Command | Description |
|---------|-------------|
| `!work` | List all available work types for your colonist and their current priorities. |
| `!work assign [work]` | Set the named work type to **priority 1** (highest) and everything else to **3**. Example: `!work assign mining` |
| `!work [work] [1-5]` | Fine-tune a single work priority. **1** = highest, **4** = lowest, **5** = disabled. Example: `!work cooking 2` |

---

## Self-Tend

| Command | Description |
|---------|-------------|
| `!selftend` | Enable **self-tending** for your colonist for **7 in-game days**. Costs **1 Skill Level point**. Cannot be re-activated while already running. |

---

## Notes

- All commands reply directly to you via Twitch chat.
- If you already have a colonist and type `!join`, you'll get a reminder instead of a duplicate spawn.
- If your colonist is hibernating, `!join` will wake them up instead of spawning a new one.
- Owner-only commands are not listed here — see `BENNY_ONLY.md` (private reference).
