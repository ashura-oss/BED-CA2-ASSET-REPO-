# Aren Identity Lock

Use these rules for every Aren body sheet and player-facing icon.

- Human village soldier from Hearthvale, early rebel era.
- Dark messy hair, scarred/serious human face, guarded expression.
- Practical dark leather over worn mail, ash-stained and road-worn.
- Torn grey march cloak with ragged holes and heavy cloth folds.
- Blackened Hearthvale sword, kept close to the body in body-only sheets.
- Leather belts, boots, bracers, and grounded soldier silhouette.
- Clean HD 2D game sprite style, painterly but gameplay-readable, not pixel art.
- 3/4 side battle view, facing toward screen-right for player-side sheets.
- Stable feet/bottom anchor and consistent body height across idle/run/action sheets.

Accepted references:

- Idle master: `public/assets/sprites/characters/aren/idle/sheet-transparent.webp`
- Run master: `public/assets/sprites/characters/aren/run/sheet-transparent.webp`
- Basic attack master: `public/assets/sprites/characters/aren/basic_attack/sheet-transparent.webp`
- Heavy attack master: `public/assets/sprites/characters/aren/heavy_attack/sheet-transparent.webp`
- Defend master: `public/assets/sprites/characters/aren/defend/sheet-transparent.webp`
- Hurt master: `public/assets/sprites/characters/aren/hurt/sheet-transparent.webp`
- Command/cast master: `public/assets/sprites/characters/aren/command_cast/sheet-transparent.webp`
- Ranged attack master: `public/assets/sprites/characters/aren/ranged_attack/sheet-transparent.webp`
- Smoke flank master: `public/assets/sprites/characters/aren/smoke_flank/sheet-transparent.webp`
- Defeat master: `public/assets/sprites/characters/aren/defeat/sheet-transparent.webp`

Prompt invariants:

- Preserve face, hair, cloak, armor, sword, proportions, palette, and art style.
- Change only the requested action pose and small clothing motion.
- Keep body sheets free of detached slash arcs, smoke, dust, projectiles, impact bursts, speed lines, and wide trails.
- Use solid flat `#FF00FF` raw background and generous cell padding.
