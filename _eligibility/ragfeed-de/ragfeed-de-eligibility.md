---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No monitoring of private individuals
    text: Insbesondere überwachen Sie keine Seiten, um eine bestimmte Privatperson zu beobachten
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Das kostenlose Konto kommt mit der Bestätigung der E-Mail-Adresse zustande.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ragfeed-de
provenance_date: '2026-11-10'
provider_name: ragfeed-de
provider_slug: ragfeed-de
slug: ragfeed-de-eligibility
source_date: '2026-11-10'
source_filename: ragfeed-de-eligibility.yml
source_heading: Eligibility
source_page: https://ragfeed.de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ragfeed-de\naid: ragfeed-de\nurl: https://ragfeed.de/agb\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No monitoring of private individuals\n  text: Insbesondere überwachen Sie keine Seiten, um eine bestimmte Privatperson zu beobachten\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Das kostenlose Konto kommt mit der Bestätigung der E-Mail-Adresse zustande.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ragfeed-de/eligibility/ragfeed-de-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from ragfeed-de's own page on 2026-11-10.
synthetic: false
tags:
- Web Scraping
- Ai Data
- EU Hosting
- Compliance
- Software-as-a-Service
---
