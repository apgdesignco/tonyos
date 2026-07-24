# Bush League

> A charming, data-driven baseball organization simulator about building a team, developing people, running a ballpark, and creating a franchise history that feels alive.

## Status

**Phase 0 — Project Foundation**

Bush League is currently in discovery and definition. No production application code has been selected or scaffolded yet.

## Product Thesis

Most sports management games are either deep but difficult to use, or accessible but shallow. Bush League aims for the middle: a credible long-term simulation presented through a friendly, readable, character-rich interface.

The player is not only setting lineups. They are running an organization:

- Build and manage a roster
- Scout, draft, train, and promote prospects
- Operate and evolve a baseball park
- Manage coaches, staff, finances, fans, and ownership expectations
- Simulate games at different levels of involvement
- Watch a fictional baseball world develop history over many seasons

## Core Experience

The default loop is:

1. Review the organization and current priorities.
2. Make a small number of meaningful decisions.
3. Simulate one game, key moments, a series, or several games.
4. Review outcomes, development, finances, and league events.
5. Continue building the franchise over seasons and decades.

## Initial Product Pillars

1. **Decisions over navigation** — organize the experience around what requires attention, not a maze of database screens.
2. **Friendly depth** — explain complex systems without removing meaningful choices.
3. **A living organization** — roster, staff, prospects, ballpark, fans, finances, and league history affect one another.
4. **Flexible pacing** — support play-by-play, key moments, quick simulation, and multi-game simulation.
5. **Statistics tell stories** — data should produce understandable narratives, rivalries, careers, records, and memories.
6. **Character without spectacle** — use stylized low-poly Blender characters and editorial presentation rather than expensive real-time realism.
7. **No manipulative grind** — progression comes from management and long-term planning, not artificial energy systems or pay-to-win mechanics.

## Planned Documentation

- `docs/product/charter.md`
- `docs/product/principles.md`
- `docs/product/scope.md`
- `docs/research/competitive-teardown.md`
- `docs/design/gameplay-loops.md`
- `docs/design/information-architecture.md`
- `docs/architecture/overview.md`
- `docs/architecture/decisions/`

## Likely Technical Direction

The current working direction is a mobile-first web application/PWA using React and TypeScript, with simulation logic separated from presentation and a relational persistence layer. This remains a hypothesis until the discovery and architecture phases are completed.

## Relationship to TonyOS

Bush League is the first full application developed inside TonyOS using its front-end-friendly product-development ecosystem. It will serve as both a real game project and a proving ground for reusable documentation, design, architecture, testing, and AI-assisted development practices.
