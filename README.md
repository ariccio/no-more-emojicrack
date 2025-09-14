# no-more-emojicrack
The extracted files I use to reduce the ocular diarrhea that LLMs seem to love to generate


Simply add this to your instructions file:
```markdown
## emoji use and stylistic text
- Use emojis only where they add clarity and value to the code. The `✗` emoji actually does work well quite often for ERRORS, and the `✓` works well for the top level successes.  Do not use them gratuitously or excessively. Do not dilute the user's attention - for many remaining use cases something less obtrusive like one of these may suffice unless something truly rare in the codebase is happening:
  **Status & Feedback:**
  "✓ ✗ ✔ ✖ ☑ ☒ ☐ ⚠ ℹ ★ ☆"

  **Shapes & Geometry:**
  "◆ ◇ ● ○ ■ □ ▪ ▫ ▶ ▷ ◀ ◁ ▲ △"

  **Arrows & Navigation:**
  "→ ← ↑ ↓ ➔ ➜ ➞ ➟ ⟳ ⟲"

  **Technical & Tools:**
  "⚙ ⚕ ※ • ☎ ☏"

  **Weather & Nature:**
  "⛈ ⛇ ⛆ ⛅︎ ⛄︎ ☔︎ ☄ ☃ ☂ ☁ ☀ ☼"

  **Human & Expression:**
  "☺ ☻ ☹ ☟ ☞ ☜ ☛ ☚ ☕︎ ⛸"

- Unicode has many other "textual representations" that are preferable to emojis. If you're considering anything about emojis, textual representations, or cool unicode in general, I have added more detailed information in `.ai/mother-effing-emojis-emojicrack-and-cool-unicode.md` - in cases like that or anything similar, please read that file.


```
