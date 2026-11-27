---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Il servizio è rivolto a professionisti, imprese, creator, agenzie
    type: business
  minimum_age:
    text: soggetti maggiorenni
    value: adult
  restricted_uses:
  - summary: Prohibited AI practices under AI Act
    text: è vietato l'uso di Bynor per pratiche vietate dal Regolamento (UE) 2024/1689 (AI Act) o da altre norme applicabili
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
name: Bynor
provenance_date: '2026-11-09'
provider_name: Bynor
provider_slug: bynor-ai
slug: bynor-ai-eligibility
source_date: '2026-11-09'
source_filename: bynor-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bynor.ai/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bynor\naid: bynor-ai\nurl: https://bynor.ai/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Il servizio è rivolto a professionisti, imprese, creator, agenzie\nrestricted_uses:\n- summary: Prohibited AI practices under AI Act\n  text: è vietato l'uso di Bynor per pratiche vietate dal Regolamento (UE) 2024/1689 (AI Act) o da altre norme applicabili\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: adult\n  text: soggetti maggiorenni\n"
source_yaml_url: https://artifacts.apis.io/bynor-ai/eligibility/bynor-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bynor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Social Media
- Automation
- Analytics
---
