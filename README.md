# CISC-S'26 - Triple-Pendulum TRNG

[Back to the project hub](https://github.com/limshoon/triple-pendulum/tree/main)

This branch preserves the ENTRIP submission to the **2026 Conference on Information Security and Cryptography - Summer (CISC-S'26)**.

![CISC-S'26 poster](assets/cisc-s-2026-poster-preview.png)

## Official record

- Paper number: `354`
- Poster session: `P1-082`
- Title: `하드웨어 삼중진자 기반 TRNG의 설계 및 보안 검증 방법론`
- Authors: Seung-Hoon Lim, Han-Sol Kim, Jae-Young Jeong, Hye-Ryeong Lee, and Prof. Jin Kwak
- Official listing: [CISC-S'26 program book](https://kiisc.or.kr/bbs/downloadBoardImage?uploadedFileId=14823)

## Focus at this stage

The CISC-S submission moves the project from a general hardware-TRNG concept toward a security-evaluation methodology:

- defines the hardware pendulum, camera, state reconstruction, raw health test, conditioning, and DRBG as separate trust-boundary components;
- treats raw motion-derived bits as internal evaluation material, not as final cryptographic output;
- proposes NIST SP 800-90B-oriented entropy assessment and NIST SP 800-22/AIS 31 statistical checks;
- identifies environmental manipulation, camera-angle changes, mechanical interference, source bias, repeated patterns, and DRBG-input policy as attack and failure surfaces;
- emphasizes long-duration stability, fail-safe behavior, and reproducible evaluation procedures as future validation requirements.

## Artifacts

- [Final CISC-S'26 paper](artifacts/cisc-s-2026-paper.pdf)
- [CISC-S'26 poster](artifacts/cisc-s-2026-poster.pdf)

## Research boundary

This submission presents design and initial security-evaluation methodology. It does not claim a certified entropy source, a completed cryptographic module, or production deployment.

## Curation note

Only the final paper and poster are included. Submission drafts, authoring files, conference templates, receipts, transfer confirmations, registration screenshots, and other administrative documents were excluded.

## Rights and reuse

These are coauthored conference materials provided for portfolio viewing. Copyright and publication rights remain with the respective authors and publisher. No reuse permission is granted without prior consent.
