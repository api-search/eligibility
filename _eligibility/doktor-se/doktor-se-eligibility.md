---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Appen får bara användas av och avse den person som kontot gäller.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for acute care
    text: Doktor.se ska inte användas vid behov av akut vård, utan då bör Kunden ringa 112 eller uppsöka akutmottagning.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: För att kunna använda Doktor.ses tjänster krävs det att Kunden kan legitimera sig med hjälp av e-legitimation (Bank-ID).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Doktor.se
provenance_date: '2026-11-09'
provider_name: Doktor.se
provider_slug: doktor-se
slug: doktor-se-eligibility
source_date: '2026-11-09'
source_filename: doktor-se-eligibility.yml
source_heading: Eligibility
source_page: https://doktor.se/allmanna-villkor
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doktor.se\naid: doktor-se\nurl: https://doktor.se/allmanna-villkor\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Appen får bara användas av och avse den person som kontot gäller.\nrestricted_uses:\n- summary: Not for acute care\n  text: Doktor.se ska inte användas vid behov av akut vård, utan då bör Kunden ringa 112 eller uppsöka akutmottagning.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: För att kunna använda Doktor.ses tjänster krävs det att Kunden kan legitimera sig med hjälp av e-legitimation\n\
  \    (Bank-ID).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/doktor-se/eligibility/doktor-se-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Doktor.se's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Telehealth
- Sweden
- Digital Health
---
