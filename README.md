# Deku Desktop Integration

Desktop composition and integration configuration for Deku Linux.

## Status

Bootstrap stage. KDE Plasma is the initial design direction, not a supported or tested desktop image yet.

## Responsibilities

- Integrate upstream KDE Plasma and required runtime components through reviewed package recipes.
- Track default application choices, session integration, accessibility settings and desktop smoke tests.
- Record upstream versions, license/provenance and any local patches.

## Non-goals

Do not fork or rewrite KDE components without a concrete upstream limitation. Package recipes live in deku-recipes; package building and system composition remain in their dedicated repositories.
