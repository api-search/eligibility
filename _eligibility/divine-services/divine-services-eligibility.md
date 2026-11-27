---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Service, you explicitly represent and warrant that you are at least 18 years old, otherwise capable of entering into binding contracts
    type: individual
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Commercial use
    text: The Service is for your personal use.
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
name: Divine Services
provenance_date: '2026-11-09'
provider_name: Divine Services
provider_slug: divine-services
slug: divine-services-eligibility
source_date: '2026-11-09'
source_filename: divine-services-eligibility.yml
source_heading: Eligibility
source_page: https://www.divinevalet.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Divine Services\naid: divine-services\nurl: https://www.divinevalet.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Service, you explicitly represent and warrant that you are at least 18 years old, otherwise\n    capable of entering into binding contracts\nrestricted_uses:\n- summary: Commercial use\n  text: The Service is for your personal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/divine-services/eligibility/divine-services-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Divine Services's own page on 2026-11-09.
synthetic: false
tags:
- Valet
- Parking
- Chauffeur
- Ohio
- Services
---
