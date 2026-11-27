---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: ARE A RESIDENT OF THE UNITED STATES AND ITS TERRITORIES.
  entity_types:
  - text: You represent that you are at least 18 years old and that the information you provide to us is accurate, complete, and current.
    type: individual
  minimum_age:
    text: ARE AT LEAST 18 YEARS OLD
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
name: SmithRx
provenance_date: '2026-11-10'
provider_name: SmithRx
provider_slug: smithrx
slug: smithrx-eligibility
source_date: '2026-11-10'
source_filename: smithrx-eligibility.yml
source_heading: Eligibility
source_page: https://smithrx.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SmithRx\naid: smithrx\nurl: https://smithrx.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: ARE A RESIDENT OF THE UNITED STATES AND ITS TERRITORIES.\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 years old and that the information you provide to us is accurate,\n    complete, and current.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: ARE AT LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/smithrx/eligibility/smithrx-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from SmithRx's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy
- Pharmacy Benefit Management
- Prescription Drugs
- Employee Benefits
- Claims
- Insurance
- Health Tech
---
