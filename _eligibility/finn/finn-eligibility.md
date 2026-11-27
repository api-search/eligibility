---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    text: Kunden können Verbraucher im Sinne von § 13 BGB und Unternehmer im Sinne von § 14 BGB mit Wohn- bzw. Geschäftssitz in Deutschland sein.
  entity_types:
  - text: Verbraucher im Sinne von § 13 BGB
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial passenger transport
    text: zur gewerblichen Personenbeförderung
  - summary: Commercial driving safety training
    text: zum gewerblichen Fahrsicherheitstraining
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: FINN behält sich vor, den Vertragsschluss mit dem Kunden vom Ergebnis einer Risiko- und Bonitätsprüfung abhängig zu machen
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Finn
provenance_date: '2026-11-09'
provider_name: Finn
provider_slug: finn
slug: finn-eligibility
source_date: '2026-11-09'
source_filename: finn-eligibility.yml
source_heading: Eligibility
source_page: https://www.finn.com/de-DE/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Finn\naid: finn\nurl: https://www.finn.com/de-DE/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - DE\n  excluded: []\n  text: Kunden können Verbraucher im Sinne von § 13 BGB und Unternehmer im Sinne von § 14 BGB mit Wohn- bzw. Geschäftssitz\n    in Deutschland sein.\nentity_types:\n- type: individual\n  text: Verbraucher im Sinne von § 13 BGB\nrestricted_uses:\n- summary: Commercial passenger transport\n  text: zur gewerblichen Personenbeförderung\n- summary: Commercial driving safety training\n  text: zum gewerblichen Fahrsicherheitstraining\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: true\n  text: FINN behält sich vor, den Vertragsschluss mit dem Kunden vom Ergebnis einer Risiko- und Bonitätsprüfung\n    abhängig zu machen\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/finn/eligibility/finn-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Finn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Automotive
- Car Subscription
- Mobility
- Leasing
- Fleet Management
---
