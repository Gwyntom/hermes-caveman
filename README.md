Caveman for Hermes

Hermes adaptations of Caveman reply style. Vibe-coded with Claude Sonnet 5.5.
English-only. Keep substance; cut fluff. Non-English messages get normal style.

Skills:
`/caveman` changes the next reply only.
`/cavemans` persists through conversation. Stop with `/cavemans off`, `stop caveman`, or `normal mode`.

Example — Why does component re-render?

Normal: “Sure! The component re-renders because an inline object prop creates a new reference on every render, which breaks memoization.”

Caveman: “Inline object prop makes new ref each render. Memo breaks. Wrap in `useMemo`.”

Can this save token usage? - Yes, but effectiveness depends on the task you give to Hermes. The heavier the expected textual outputs are, the more effective /caveman is in saving your previous tokens (〜-30% in heavy textual output tasks).

On the contrary, if your given task is too simple, there is a possibility that /caveman costs a bit more tokens. This is because calling a skill entails a bit extra cost. If the amount of tokens you saved for outputs with /caveman do not outweigh the cost of calling the skill, it might conversely costs you 5-10% more tokens.

Install either or both:

```sh
hermes skills install https://raw.githubusercontent.com/Gwyntom/hermes-caveman/main/caveman/SKILL.md --name caveman
hermes skills install https://raw.githubusercontent.com/Gwyntom/hermes-caveman/main/cavemans/SKILL.md --name cavemans
```

Credits and licenses:
Original Caveman skill by JuliusBrussee: https://github.com/JuliusBrussee/caveman
Upstream v2.2.0 skill uses MIT. Included Hermes skill files declare Apache-2.0 in their frontmatter. See `LICENSE-MIT` and `LICENSE-APACHE-2.0`; licenses cover their respective source material, not a blanket dual-license grant for every file.
`/cavemans` is a Hermes-specific session-wide adaptation. No proxy or runtime code included.
