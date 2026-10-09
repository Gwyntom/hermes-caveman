Caveman for Hermes

Hermes adaptations of Caveman reply style. Vibe-coded with Claude Sonnet 5.5.
English-only. Keep substance; cut fluff. Non-English messages get normal style.

Skills:
`/caveman` changes the next reply only.
`/cavemans` persists through conversation. Stop with `/cavemans off`, `stop caveman`, or `normal mode`.

Example — Why does component re-render?

Normal: “Sure! The component re-renders because an inline object prop creates a new reference on every render, which breaks memoization.”

Caveman: “Inline object prop makes new ref each render. Memo breaks. Wrap in `useMemo`.”

Install either or both:

```sh
hermes skills install https://raw.githubusercontent.com/Gwyntom/hermes-caveman/main/caveman/SKILL.md --name caveman
hermes skills install https://raw.githubusercontent.com/Gwyntom/hermes-caveman/main/cavemans/SKILL.md --name cavemans
```

Credits and licenses:
Original Caveman skill by JuliusBrussee: https://github.com/JuliusBrussee/caveman
Upstream v2.2.0 skill uses MIT. Included Hermes skill files declare Apache-2.0 in their frontmatter. See `LICENSE-MIT` and `LICENSE-APACHE-2.0`; licenses cover their respective source material, not a blanket dual-license grant for every file.
`/cavemans` is a Hermes-specific session-wide adaptation. No proxy or runtime code included.
