---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: The Service may not be used or otherwise provided or made available, either directly or indirectly, (a) in Cuba, Iran, North Korea, Syria, Crimea region of Ukraine, or any other country subject to U.S. trade sanctions
  entity_types:
  - text: If you are under 18 years of age, you are not authorized to use the Service with or without registering.
    type: individual
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Service with or without registering.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: The Service is solely for your personal, non-commercial use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ezra
provenance_date: '2026-11-09'
provider_name: Ezra
provider_slug: ezra
slug: ezra-eligibility
source_date: '2026-11-09'
source_filename: ezra-eligibility.yml
source_heading: Eligibility
source_page: https://www.ezra.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ezra\naid: ezra\nurl: https://www.ezra.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: The Service may not be used or otherwise provided or made available, either directly or indirectly, (a)\n    in Cuba, Iran, North Korea, Syria, Crimea region of Ukraine, or any other country subject to U.S. trade sanctions\nentity_types:\n- type: individual\n  text: If you are under 18 years of age, you are not authorized to use the Service with or without registering.\nrestricted_uses:\n- summary: No commercial use\n  text: The Service\
  \ is solely for your personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Service with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/ezra/eligibility/ezra-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ezra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Imaging
- Preventive Health
- Cancer Screening
- MRI
- Diagnostics
---
