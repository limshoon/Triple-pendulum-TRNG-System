# ASK 2026 - Triple-Pendulum TRNG

[Back to the project hub](https://github.com/limshoon/triple-pendulum/tree/main)

This branch preserves the ENTRIP submission to **ASK 2026 (Annual Symposium of the Korea Information Processing Society)**.

## Result

**Bronze Award, Undergraduate Paper Competition**

- Paper ID: `KIPS_C2026A0106`
- Title: `하드웨어 삼중진자 기반 진난수 생성 시스템의 설계 및 초기 검증`
- English title: *Design and Initial Validation of a Hardware Triple-Pendulum True Random Number Generation System*
- Official record: [ASK 2026 program](https://ask.kips.or.kr/programBook)

## Scope at this stage

The ASK paper captures the project's initial research architecture:

- compound triple-pendulum dynamics and RK4-based simulation;
- browser-based visualization and precheck environment;
- camera-based trajectory acquisition and state reconstruction;
- raw motion-derived sequence generation;
- experimental direct-output and HMAC_DRBG-assisted paths;
- initial local statistical checks and clearly stated validation limits.

The paper treats the physical motion as an entropy-source candidate. It does not claim that raw motion data is immediately suitable as cryptographic output or that formal certification has been completed.

## Artifact

- [Final ASK 2026 paper](artifacts/ask-2026-paper.pdf)

## Team

Seung-Hoon Lim, Han-Sol Kim, Jae-Young Jeong, Hye-Ryeong Lee, and Prof. Jin Kwak - Ajou University.

## Curation note

Only the published-format paper is included. Drafts, templates, receipts, accommodation and railway records, and other administrative documents were excluded.

## Rights and reuse

This is a coauthored competition paper provided for portfolio viewing. Copyright and publication rights remain with the respective authors and publisher. No reuse permission is granted without prior consent.
