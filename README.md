# cloud-itonami-lei-549300g8zpnq5dni6a45

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by Grab Holdings Inc.**

This repository archives the publicly published Singapore Terms of Service:
Transport, Delivery and Logistics of **Grab Holdings Inc.**, with source-url and
retrieval-date provenance, per
[ADR-2607110300](https://github.com/com-junkawasaki/root/blob/main/90-docs/adr/2607110300-cloud-itonami-lei-corporate-tos-catalog.edn)
(`cloud-itonami-lei-corporate-tos-catalog`, `com-junkawasaki/root`). It is a read-only
reference/archive repository — it does not act, propose, or execute anything on the
company's behalf, and is not a governed Advisor/Governor actor.

## Company identity

- **Legal name**: Grab Holdings Inc.
- **LEI (ISO 17442)**: [549300G8ZPNQ5DNI6A45](https://search.gleif.org/#/record/549300G8ZPNQ5DNI6A45) (GLEIF-verified, status ACTIVE, registration ISSUED)
- **Jurisdiction**: KY (Cayman Islands, incorporation); operational HQ Singapore
- **Website**: https://www.grab.com
- **Ticker**: GRAB (Nasdaq)

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of archived Terms of Service documents.
- `NOTICE` — copyright/attribution statement for the archived third-party text.
- `blueprint.edn` — machine-readable company identity record.

## Related cloud-itonami blueprint (passenger-road-transport vertical)

Grab operates one of Southeast Asia's largest ride-hailing/taxi-dispatch
networks across Singapore, Malaysia, Indonesia, the Philippines, Vietnam,
Thailand and Cambodia — `cloud-itonami-isic-4921`'s own README names "taxi/
rideshare dispatch" explicitly in its scope. This vertical's *generic, forkable*
Open Business Blueprint counterpart in the `cloud-itonami` fleet is
[`cloud-itonami-isic-4921`](https://github.com/cloud-itonami/cloud-itonami-isic-4921)
(ISIC 4921/4922 sibling pair — urban/suburban vs. intercity/chartered coach
scheduling-and-dispatch coordination, Advisor⊣Governor actor pattern). This
LEI-catalog entry is a **read-only ToS reference only** — it is not a fork of, and
has no code dependency on, isic-4921.

Noted for context, not asserted as legal analysis: Grab's own Terms of Service
(Section 21.2) explicitly states Grab "does not warrant or represent that it
assesses or monitors the suitability, legality, ability, movement or location of
any Consumers or Partners" and disclaims liability arising from its driver-
partners. This is a materially different verification posture from
`transitops.governor`'s own architecture, which structurally requires
independent, store-derived verification of vehicle registration and operator
licensing *before* any dispatch-scheduling proposal may ever commit or escalate
— see `cloud-itonami-isic-4921/docs/real-world-tos-governor-analysis.md` for the
fuller, evidence-cited comparison across this catalog.

## Design rationale

See ADR-2607110300 in `com-junkawasaki/root` (`90-docs/adr/`).
