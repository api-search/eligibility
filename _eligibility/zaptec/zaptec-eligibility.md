---
api_specs:
- filename: zaptec-chargehistory-api-openapi.yml
  format: yaml
  label: Zaptec Charge History API
  slug: zaptec-chargehistory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zaptec/openapi/zaptec-chargehistory-api-openapi.yml
- filename: zaptec-charger-api-openapi.yml
  format: yaml
  label: Zaptec Charger API
  slug: zaptec-charger-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zaptec/openapi/zaptec-charger-api-openapi.yml
- filename: zaptec-chargerfirmware-api-openapi.yml
  format: yaml
  label: Zaptec Charger Firmware API
  slug: zaptec-chargerfirmware-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zaptec/openapi/zaptec-chargerfirmware-api-openapi.yml
- filename: zaptec-constants-api-openapi.yml
  format: yaml
  label: Zaptec Constants API
  slug: zaptec-constants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zaptec/openapi/zaptec-constants-api-openapi.yml
- filename: zaptec-installation-api-openapi.yml
  format: yaml
  label: Zaptec Installation API
  slug: zaptec-installation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zaptec/openapi/zaptec-installation-api-openapi.yml
- filename: zaptec-session-api-openapi.yml
  format: yaml
  label: Zaptec Session API
  slug: zaptec-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zaptec/openapi/zaptec-session-api-openapi.yml
- filename: zaptec-user-group-api-openapi.yml
  format: yaml
  label: Zaptec User Group API
  slug: zaptec-user-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zaptec/openapi/zaptec-user-group-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To register, You must be over 18 years of age and provide a valid email address, address, Your name and Your country of residence.
    type: individual
  - text: '"You", "Your" or "User" means a user of Zaptec Products and Cloud Services, including both consumers, partners and users engaged in business activities.'
    type: business
  minimum_age:
    text: To register, You must be over 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unauthorised account sharing
    text: allow unauthorised persons, partners or businesses access to or use of Zaptec Cloud Services or using any other person's login credentials
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
name: Zaptec
provenance_date: '2026-11-10'
provider_name: Zaptec
provider_slug: zaptec
slug: zaptec-eligibility
source_date: '2026-11-10'
source_filename: zaptec-eligibility.yml
source_heading: Eligibility
source_page: https://www.zaptec.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zaptec\naid: zaptec\nurl: https://www.zaptec.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To register, You must be over 18 years of age and provide a valid email address, address, Your name and\n    Your country of residence.\n- type: business\n  text: '\"You\", \"Your\" or \"User\" means a user of Zaptec Products and Cloud Services, including both consumers, partners\n    and users engaged in business activities.'\nrestricted_uses:\n- summary: Unauthorised account sharing\n  text: allow unauthorised persons, partners\
  \ or businesses access to or use of Zaptec Cloud Services or using any\n    other person's login credentials\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To register, You must be over 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/zaptec/eligibility/zaptec-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Zaptec's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EV Charging
- Smart Charging
- Energy
- Sustainability
- Platform
---
