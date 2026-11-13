# The Frog Prince FABLE 5.2

An enhanced-graphics edition of The Frog Prince, a fairy-tale platformer:
hop across lilypads through ten scenes to reach the prince, earning a new
piece of royal clothing with every level.

The classic version lives at https://2d-platformer-one.vercel.app/
(source: michaelnmadani/2dPlatformer).

## Play locally

It's a static site with no build step:

```bash
npx serve . -p 3000
# or
python3 -m http.server 3000
```

## Controls

- Move: arrow keys or A / D
- Jump: Space, W or Up (hold to jump higher)
- Pause: P or Esc; Q from the pause menu returns to level select
- Sound: M
- Touch devices get on-screen buttons

## What's in this edition

- Per-scene ambient effects, water reflections and ripples, color grading
- Redesigned title, level select, HUD and results screens
- Golden flies to collect, 3-star ratings, level timer and best times
- Checkpoints on levels 6-10, coyote time and jump buffering
- Generated music based on Debussy's Clair de Lune, plus scene ambience

## Credits

- Heading font: Cinzel, SIL Open Font License 1.1 (see fonts/LICENSE.txt)
- Music: arrangement after Claude Debussy's "Clair de Lune" (public domain)
