# DeDust Observatory

## О проекте / токене

DUST is the governance token for the DeDust Protocol.

Самоописание из метаданных токена; заявления проекта не проверены независимо.

Источники (проверены 2026-11-25):

- <https://tonapi.io/v2/jettons/EQBlqsm144Dq6SjbPI4jjZvA1hqTIP3CvHovbIfW_t-SCALE>
- <https://dedust.io/>

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
The bundled snapshot contains on-chain holders, successful native TON swaps, burn scans, historical TON/USD rates and indexed pools. Year history and wallet badge enrichment are incremental; section freshness is shown in the interface.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
GitHub Actions is configured at 17 and 47 minutes of each hour (UTC). Scheduled execution may be delayed by GitHub. The shared Cloudflare runner was not modified.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.
