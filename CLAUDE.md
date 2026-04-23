# Project: adea-it.no

## What this is
Firmaweb for Adea IT AS. LIVE via GitHub Pages med custom domain (adea-it.no). Enkel single-page profil med kontaktinfo.

## Stack
- Static HTML/CSS (ingen build step)
- GitHub Pages hosting (CNAME adea-it.no)
- Deployment: push til main-branch

## Architecture
- `index.html` — Hele firmasiden (14 KB)
- `CNAME` — custom domain
- `.nojekyll` — skrur av Jekyll-prosessering

## Conventions
- Business-e-post `nevzat@adea-it.no` for kontakt, aldri personlig
- Org.nr + by/land OK i footer, aldri gateadresse (se `feedback_never_leak_personal_info`)

## Do NOT touch
- `CNAME` — custom domain
- `.nojekyll` — trengs for at GitHub Pages skal servere rå HTML

## Key behaviors
- Deployment automatisk ved push til main
- Ingen dynamikk, ingen JS-avhengigheter
