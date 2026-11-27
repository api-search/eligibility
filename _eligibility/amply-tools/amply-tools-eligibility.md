---
api_specs:
- filename: amply-tools-openapi-generated.yml
  format: yaml
  label: Amply API
  slug: amply-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amply-tools/openapi/_ae-authored/amply-tools-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: (currently, Cuba, Iran, North Korea, Syria, the Crimea region of Ukraine, and the Donetsk People’s Republic or Luhansk People’s Republic)
  entity_types:
  - text: the entity on whose behalf the individual accepting this Agreement accepts this Agreement
    type: business
  - text: Where you access or use the Software as a consumer (that is, for purposes outside your trade, business, craft or profession)
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned countries and persons
    text: Customer must not access, use, import, or export the Software
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to use the Software, the Customer must register for an account.
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
name: Amply
provenance_date: '2026-11-09'
provider_name: Amply
provider_slug: amply-tools
slug: amply-tools-eligibility
source_date: '2026-11-09'
source_filename: amply-tools-eligibility.yml
source_heading: Eligibility
source_page: https://amply.tools/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amply\naid: amply-tools\nurl: https://amply.tools/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: (currently, Cuba, Iran, North Korea, Syria, the Crimea region of Ukraine, and the Donetsk People’s Republic\n    or Luhansk People’s Republic)\nentity_types:\n- type: business\n  text: the entity on whose behalf the individual accepting this Agreement accepts this Agreement\n- type: individual\n  text: Where you access or use the Software as a consumer (that is, for purposes outside your trade, business,\n    craft or profession)\nrestricted_uses:\n\
  - summary: Sanctioned countries and persons\n  text: Customer must not access, use, import, or export the Software\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to use the Software, the Customer must register for an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amply-tools/eligibility/amply-tools-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Amply's own page on 2026-11-09.
synthetic: false
tags:
- Personalization
- Mobile
- SDK
- In-App
- Analytics
---
