---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: För att använda 3Community behöver du ha fyllt 18 år.
    type: individual
  minimum_age:
    text: För att använda 3Community behöver du ha fyllt 18 år.
    value: '18'
  restricted_uses:
  - summary: Language
    text: Användare får inte använda andra språk än svenska eller engelska på forumet
  - summary: Harassment or abusive content
    text: Användare får inte skriva rasistiska, sexistiska, diskriminerande, hotande eller på annat sätt förolämpande kommentarer.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tre (Hi3G)
provenance_date: '2026-11-10'
provider_name: Tre (Hi3G)
provider_slug: tre-se
slug: tre-se-eligibility
source_date: '2026-11-10'
source_filename: tre-se-eligibility.yml
source_heading: Eligibility
source_page: https://community.tre.se/site/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tre (Hi3G)\naid: tre-se\nurl: https://community.tre.se/site/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: För att använda 3Community behöver du ha fyllt 18 år.\nrestricted_uses:\n- summary: Language\n  text: Användare får inte använda andra språk än svenska eller engelska på forumet\n- summary: Harassment or abusive content\n  text: Användare får inte skriva rasistiska, sexistiska, diskriminerande, hotande eller på annat sätt förolämpande\n    kommentarer.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: För att använda 3Community behöver du ha fyllt 18 år.\n"
source_yaml_url: https://artifacts.apis.io/tre-se/eligibility/tre-se-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tre (Hi3G)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
---
