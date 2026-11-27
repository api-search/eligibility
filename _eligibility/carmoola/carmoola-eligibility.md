---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Finance is subject to status and is only available to UK residents aged 18 and over.
  entity_types:
  - text: This website is provided for domestic and private use.
    type: individual
  minimum_age:
    text: only available to UK residents aged 18 and over
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: You agree not to use this website for any commercial or business purposes
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
name: Carmoola
provenance_date: '2026-11-09'
provider_name: Carmoola
provider_slug: carmoola
slug: carmoola-eligibility
source_date: '2026-11-09'
source_filename: carmoola-eligibility.yml
source_heading: Eligibility
source_page: https://www.carmoola.co.uk/legal/terms-conditions-website
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carmoola\naid: carmoola\nurl: https://www.carmoola.co.uk/legal/terms-conditions-website\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Finance is subject to status and is only available to UK residents aged 18 and over.\nentity_types:\n- type: individual\n  text: This website is provided for domestic and private use.\nrestricted_uses:\n- summary: No commercial use\n  text: You agree not to use this website for any commercial or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: only available\
  \ to UK residents aged 18 and over\n"
source_yaml_url: https://artifacts.apis.io/carmoola/eligibility/carmoola-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Carmoola's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Automotive
- Car Finance
- Lending
- Consumer Credit
- United Kingdom
- Mobile App
---
