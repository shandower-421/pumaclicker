# 🐆 PumaClicker

A browser-based idle clicker game. Click the puma. Earn pets. Build an empire of affection.

## Play

Open `PumaClicker.html` in any modern browser. No server, no build step, no dependencies.

## How to Play

**Click** the puma to earn pets. **Spend** pets in the Shop to unlock passive income. The puma earns pets for you automatically — even when you're not clicking.

### Happiness

Your puma has feelings. Constant petting spikes happiness above 100, then it crashes. Low happiness reduces passive income. Let the puma breathe between clicking sessions.

### Shop

13 upgrades ranging from a Treat Bag (10 pets) to Puma God Mode (10 billion pets). Each upgrade purchased increases the cost of the next one, so timing matters.

### Transcendence

Once you accumulate enough lifetime pets, a Transcend button appears. Transcending resets your progress but grants a permanent **1.5× income multiplier** — stacking with each subsequent transcendence.

## Technical Notes

- Single-file HTML — all CSS and JS inline, no external dependencies except Google Fonts
- `requestAnimationFrame` game loop with dirty-checked DOM writes
- Compositor-safe animations (opacity-only transitions, no layout repaints)
- `localStorage` for onboarding state (resets on clear)
- WCAG AA contrast verified on all text colors
- Responsive: works on mobile, tablet, and desktop
- Respects `prefers-reduced-motion`

## Cheats

Open the browser console. The puma sees you.
