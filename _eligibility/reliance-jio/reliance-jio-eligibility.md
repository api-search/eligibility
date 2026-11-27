---
api_specs:
- filename: reliance-jio-jioeventscpaasplatform-api-openapi.yml
  format: yaml
  label: Reliance Jio Events Cpaas Platform API
  slug: reliance-jio-jioeventscpaasplatform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reliance-jio/openapi/reliance-jio-jioeventscpaasplatform-api-openapi.yml
- filename: reliance-jio-jiomeetcpaasplatform-api-openapi.yml
  format: yaml
  label: Reliance Jio Meet Cpaas Platform API
  slug: reliance-jio-jiomeetcpaasplatform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reliance-jio/openapi/reliance-jio-jiomeetcpaasplatform-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We accept payments made by most of the major credit/debit cards issued in India. All payments made against the purchases of Service(s) on Website by you shall be in Indian Rupees only.
  entity_types:
  - text: The Service(s) and Application are provided for your personal, and non-commercial use only.
    type: individual
  minimum_age:
    text: In order to use and or register with the Website you must be 18 (Eighteen) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only (app)
    text: The Service(s) and Application are provided for your personal, and non-commercial use only.
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
name: Reliance Jio
provenance_date: '2026-11-10'
provider_name: Reliance Jio
provider_slug: reliance-jio
slug: reliance-jio-eligibility
source_date: '2026-11-10'
source_filename: reliance-jio-eligibility.yml
source_heading: Eligibility
source_page: https://www.jio.com/jcms/en-in/general-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reliance Jio\naid: reliance-jio\nurl: https://www.jio.com/jcms/en-in/general-terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We accept payments made by most of the major credit/debit cards issued in India. All payments made against\n    the purchases of Service(s) on Website by you shall be in Indian Rupees only.\nentity_types:\n- type: individual\n  text: The Service(s) and Application are provided for your personal, and non-commercial use only.\nrestricted_uses:\n- summary: Personal, non-commercial use only (app)\n  text: The Service(s) and Application are\
  \ provided for your personal, and non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to use and or register with the Website you must be 18 (Eighteen) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/reliance-jio/eligibility/reliance-jio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Reliance Jio's own page on 2026-11-10.
synthetic: false
tags:
- Telecommunications
- India
- Mobile Network Operator
- Network APIs
- CAMARA
- Open Gateway
- SIM Swap
- Identity Verification
- CPaaS
- Messaging
- Voice
- IoT
- Broadband
- 5G
- BSS
- OSS
- Standards
- Video Conferencing
---
