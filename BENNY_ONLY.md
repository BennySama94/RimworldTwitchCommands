# Benny-Only Commands

These commands are restricted to the **channel owner** (`BennySama94`) in Twitch chat.
Viewers cannot use these — they are for debug and colony management purposes only.

---

## Colonist Management

| Command | Description |
|---------|-------------|
| `!die [colonist]` | Immediately removes the named colonist from the colony. Uses the Twitch username. Example: `!die SomeViewer` |
| `!hibernate [colonist]` | Despawns the colonist and puts them into **hibernation** (stored safely in WorldPawns). They won't count against the colony but won't be lost either. Example: `!hibernate SomeViewer` |
| `!wakeup [colonist]` | Retrieves a hibernating colonist and re-spawns them back into the colony. Example: `!wakeup SomeViewer` |

---

## Debug / Testing

| Command | Description |
|---------|-------------|
| `!levelup [user]` | Grants the named viewer **1 level-up** worth of EXP instantly. |
| `!levelup [user] [n]` | Grants the named viewer **n** level-ups instantly. Example: `!levelup SomeViewer 3` |

---

## Notes

- These commands are checked against your Twitch username at runtime — they silently do nothing if typed by anyone else.
- `!hibernate` / `!wakeup` is useful for managing the colony size during raids or performance-heavy moments without permanently losing a viewer's colonist.
- `!die` is a hard removal (destroys the pawn). Use `!hibernate` if you want to keep the colonist around.
- `!levelup` is for testing the progression system. Replies with a `[DEBUG]` message showing before/after level and point totals.
