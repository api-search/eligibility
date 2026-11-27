---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: För att bli kund måste du vara myndig (18 år eller äldre) och ha juridisk rätt att ingå avtal.
    type: individual
  - text: Medlemskapet är personligt och gäller en privatperson per medlemsnummer, registrerat i ditt namn.
    type: individual
  minimum_age:
    text: För att bli kund måste du vara myndig (18 år eller äldre)
    value: '18'
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
name: Linas Matkasse
provenance_date: '2026-11-09'
provider_name: Linas Matkasse
provider_slug: linas-matkasse
slug: linas-matkasse-eligibility
source_date: '2026-11-09'
source_filename: linas-matkasse-eligibility.yml
source_heading: Eligibility
source_page: https://www.linasmatkasse.se/villkor
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Linas Matkasse\naid: linas-matkasse\nurl: https://www.linasmatkasse.se/villkor\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: För att bli kund måste du vara myndig (18 år eller äldre) och ha juridisk rätt att ingå avtal.\n- type: individual\n  text: Medlemskapet är personligt och gäller en privatperson per medlemsnummer, registrerat i ditt namn.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: För att bli kund måste du vara myndig (18 år eller\
  \ äldre)\n"
source_yaml_url: https://artifacts.apis.io/linas-matkasse/eligibility/linas-matkasse-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Linas Matkasse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Food and Beverage
- E-Commerce
- Subscription
- Meal Kit
- Grocery Delivery
- Sweden
- Scandinavia
---
