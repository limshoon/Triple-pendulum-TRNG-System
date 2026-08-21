# Ajou Masterclass 2026 - ENTRIP Final Presentation

[Back to the project hub](https://github.com/limshoon/triple-pendulum/tree/main)

This branch preserves the final ENTRIP presentation from the **2026 Ajou Masterclass** campus program, developed by team `삼중링키지`.

## What advanced in this stage

The Masterclass work refines the earlier competition concept into a more quantitative and security-conscious model:

- reframes the **camera sensor noise** as the modeled primary noise source and the **triple-pendulum dynamics** as a physical sampler/scrambler with an additional motion-driven channel;
- models 120 fps camera observation and link-specific tracking noise;
- defines state-transition events instead of harvesting low-order angle bits directly;
- separates raw-event generation, RCT/APT-style online health checks, SHA-256 conditioning, and final output;
- reports preliminary initial-condition sensitivity, session-distance, event-origin, and local statistical-precheck results;
- distinguishes remote, local-observer, and active-attack threat models;
- records the remaining work required for fixed-marker noise measurement, large-sample SP 800-90B evaluation, raw capture validation, and hardware confirmation.

## Artifact

- [Final Masterclass presentation](artifacts/ajou-masterclass-2026-final-presentation.pdf) - 36 slides

## Interpretation boundary

The quantitative values in the presentation are preliminary results from simulation and an observation model unless a slide explicitly states otherwise. They are design evidence and research-direction indicators, not formal hardware entropy certification. Slides that mention future KCI publication describe a plan, not a completed publication.

## Curation note

The final presentation was visually reviewed in full before publication. Applications, funding forms, activity logs, signatures, receipts, bank records, transport evidence, identity copies, and backup drafts were excluded.

## Team

Team `삼중링키지`, Ajou University.

## Rights and reuse

This is a coauthored campus-program presentation provided for portfolio viewing. Copyright remains with the respective authors. No reuse permission is granted without prior consent.
