---
api_specs:
- filename: steamwebapi-com-openapi-generated.yml
  format: yaml
  label: steamwebapi-com API
  slug: steamwebapi-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steamwebapi-com/openapi/_ae-authored/steamwebapi-com-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: They apply to private consumers and to entrepreneurs (B2B) alike
    type: individual
  - text: They apply to private consumers and to entrepreneurs (B2B) alike
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Steam Guard accounts
    text: The user may use the Authenticator Functionality exclusively for Steam accounts that the user personally owns or that the user is demonstrably and lawfully authorised to administer
  - summary: Critical applications
    text: It is not intended for — and the operator expressly warns against using it in — security-critical, business-critical, financial, safety-critical, or otherwise critical applications
  - summary: Sanctioned parties
    text: undertakes not to use the Service in violation of any such sanctions or export-control law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Authentication of human users is performed exclusively through the Steam OpenID flow
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: steamwebapi-com
provenance_date: '2026-11-10'
provider_name: steamwebapi-com
provider_slug: steamwebapi-com
slug: steamwebapi-com-eligibility
source_date: '2026-11-10'
source_filename: steamwebapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.steamwebapi.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: steamwebapi-com\naid: steamwebapi-com\nurl: https://www.steamwebapi.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: They apply to private consumers and to entrepreneurs (B2B) alike\n- type: business\n  text: They apply to private consumers and to entrepreneurs (B2B) alike\nrestricted_uses:\n- summary: Steam Guard accounts\n  text: The user may use the Authenticator Functionality exclusively for Steam accounts that the user personally\n    owns or that the user is demonstrably and lawfully authorised to administer\n\
  - summary: Critical applications\n  text: It is not intended for — and the operator expressly warns against using it in — security-critical, business-critical,\n    financial, safety-critical, or otherwise critical applications\n- summary: Sanctioned parties\n  text: undertakes not to use the Service in violation of any such sanctions or export-control law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Authentication of human users is performed exclusively through the Steam OpenID flow\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/steamwebapi-com/eligibility/steamwebapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from steamwebapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Steam
- Gaming
- Marketplace
- Inventory
---
