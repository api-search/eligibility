---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Regulated industry data (HIPAA, FISMA, GLBA)
    text: The Services are not tailored to comply with industry-specific regulations in the United States, including but not limited to the Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.
  - summary: Fail-safe critical environments
    text: THE APP IS NOT INTENDED FOR USE IN ENVIRONMENTS REQUIRING FAIL-SAFE PERFORMANCE.
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
name: Aiden Auto
provenance_date: '2026-11-09'
provider_name: Aiden Auto
provider_slug: aiden-auto
slug: aiden-auto-eligibility
source_date: '2026-11-09'
source_filename: aiden-auto-eligibility.yml
source_heading: Eligibility
source_page: https://aidenauto.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aiden Auto\naid: aiden-auto\nurl: https://aidenauto.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: you, whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Regulated industry data (HIPAA, FISMA, GLBA)\n  text: The Services are not tailored to comply with industry-specific\
  \ regulations in the United States, including\n    but not limited to the Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security\n    Management Act (FISMA), etc.\n- summary: Fail-safe critical environments\n  text: THE APP IS NOT INTENDED FOR USE IN ENVIRONMENTS REQUIRING FAIL-SAFE PERFORMANCE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/aiden-auto/eligibility/aiden-auto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Aiden Auto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Connected Vehicles
- Mobility
- Telematics
- Android Automotive
- Fleet Management
- Vehicle Data
- In-Vehicle Payments
- Consent Management
---
