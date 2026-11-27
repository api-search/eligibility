---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: osoba fizyczna posiadającą pełną zdolność do czynności prawnych
    type: individual
  - text: osoba prawna
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal content in queries
    text: 'Zapytanie oraz jego załączniki nie mogą zawierać: Nielegalnych Treści'
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
name: Oferteo
provenance_date: '2026-11-10'
provider_name: Oferteo
provider_slug: oferteo
slug: oferteo-eligibility
source_date: '2026-11-10'
source_filename: oferteo-eligibility.yml
source_heading: Eligibility
source_page: https://www.oferteo.pl/regulamin.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oferteo\naid: oferteo\nurl: https://www.oferteo.pl/regulamin.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: osoba fizyczna posiadającą pełną zdolność do czynności prawnych\n- type: business\n  text: osoba prawna\nrestricted_uses:\n- summary: No illegal content in queries\n  text: 'Zapytanie oraz jego załączniki nie mogą zawierać: Nielegalnych Treści'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/oferteo/eligibility/oferteo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Oferteo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Services
- Poland
- Contractors
- Quotes
- Reviews
- Local Services
---
