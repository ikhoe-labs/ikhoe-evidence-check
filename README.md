# IKHOE Evidence Check

**Deterministic data-quality auditing with evidence you can inspect and verify.**

> **PROGRESSING · Level 3/5 · 58/100** — public product active; broader IKHOE platform remains evidence-gated.
>
> See [`STATUS.md`](STATUS.md) for the current public progress and evidence boundary.

## What IKHOE is building

IKHOE Labs is developing an evidence-first operational intelligence stack. The public product is intentionally narrow: **IKHOE Evidence Check** turns a supplied CSV into deterministic quality signals and an inspectable evidence record.

The broader IKHOE architecture is being developed privately around a simple operational rule:

> `implemented != functioning != connected != executed != evidenced`

A capability is not promoted to operational status merely because code exists. Execution, real effects, provenance, and evidence must be observed before stronger claims are made.

## Current product

IKHOE Evidence Check helps teams inspect CSV datasets before analysis, reporting, automation, or AI/data workflows. It can surface observable signals such as schema structure, missing values, exact duplicate rows, an input SHA-256 fingerprint, and a deterministic audit run identifier.

**Current offer:** COP 39,900/month.

**Product landing:** `public/index.html`.

**Checkout:** https://cohere-api.lemonsqueezy.com/checkout/buy/29ddd963-ec5a-40cf-a9d0-e6e51401b25c

## Who it is for

- Consultants working with client spreadsheets and CSV exports
- Small businesses preparing operational data for decisions
- Finance and accounting teams checking datasets before analysis
- AI/data teams validating inputs before pipelines
- Developers integrating deterministic data checks into workflows

## Public API

Production API: https://ikhoe-evidence-check-api.vercel.app

Health check: https://ikhoe-evidence-check-api.vercel.app/api/health

## Evidence model

Evidence Check distinguishes an observed record from independent verification. An artifact can be **recorded** when the API fingerprints and inspects it. It is **verified** only when an independently supplied SHA-256 expectation matches the observed artifact. If that expectation is absent, the system does not self-certify the result as independently verified.

This conservative model is part of the product direction: claims should be traceable to evidence rather than inferred from implementation state.

## Product family and roadmap

### Available now

**Evidence Check** — deterministic CSV data-quality evidence.

**Evidence API** — programmatic access for integration workflows.

### In development / gated

**Governed Automation** — bounded execution with explicit authorization and evidence gates.

**Operational Trust** — enterprise-oriented assurance around real operational evidence, provenance, execution, and verification.

These future surfaces are not represented as fully operational until their relevant runtime paths are demonstrated.

## Current development milestone

The private IKHOE stack has advanced from static architecture toward an operational proof model involving capability selection, bounded execution, evidence collection, and re-audit. The next critical proof is the complete GitHub → HomeCity (Windows) → real action → evidence → GitHub → independent verification loop, repeated consecutively without manual result fabrication.

That milestone is deliberately **not** claimed as complete here until it is empirically demonstrated.

## Public repository boundary

This repository is a public product and documentation surface. It intentionally does **not** contain private implementation, proprietary algorithms, internal automation, private infrastructure configuration, credentials, secrets, private prompts, or commercial strategy.

Do not add secrets, `.env` files, access tokens, private keys, internal source code, or confidential operational material to this repository.

## Limitations

Evidence Check reports observable signals about the supplied dataset. It does not guarantee that a dataset is truthful, complete, business-correct, or suitable for a particular downstream decision.

## Status

**Public product: available.** The landing page and production API are published; the commercial surface is being developed conservatively. Broader IKHOE automation and operational-assurance capabilities remain gated by runtime evidence.

## Contact

Use the product landing page for product and integration information.
