---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    - BY
    served: []
    text: comprehensive U.S. or EU sanctions (including, but not limited to, Cuba, Iran, North Korea, Syria, the Russian Federation, the Republic of Belarus, and the comprehensively sanctioned regions of Ukraine)
  entity_types:
  - text: the corporate entity or organisation accessing the Platform
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: access to production environments (permitting active commercial operations) remains strictly subject to Cargofy’s vetting protocols and the execution of requisite commercial agreements.
excluded_countries:
- CU
- IR
- KP
- SY
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cargofy
provenance_date: '2026-11-09'
provider_name: Cargofy
provider_slug: cargofy
slug: cargofy-eligibility
source_date: '2026-11-09'
source_filename: cargofy-eligibility.yml
source_heading: Eligibility
source_page: https://cargofy.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cargofy\naid: cargofy\nurl: https://cargofy.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  - BY\n  text: comprehensive U.S. or EU sanctions (including, but not limited to, Cuba, Iran, North Korea, Syria, the Russian\n    Federation, the Republic of Belarus, and the comprehensively sanctioned regions of Ukraine)\nentity_types:\n- type: business\n  text: the corporate entity or organisation accessing the Platform\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: access to production environments\
  \ (permitting active commercial operations) remains strictly subject to\n    Cargofy’s vetting protocols and the execution of requisite commercial agreements.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cargofy/eligibility/cargofy-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Cargofy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Artificial Intelligence
- Digital Workers
- Freight
- Transportation
- Software-as-a-Service
---
