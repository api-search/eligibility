---
api_specs:
- filename: agorean-com-openapi-generated.yml
  format: yaml
  label: Agorean API
  slug: agorean-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agorean-com/openapi/_ae-authored/agorean-com-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old , and you must be legally able to enter into a contract.
    type: individual
  - text: If you are agreeing on behalf of a company, you confirm you are authorised to do so.
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons and territories
    text: anything to or from a person, entity or jurisdiction subject to economic or trade sanctions of the European Union, the United Nations, the United Kingdom or the United States;
  - summary: Child sexual abuse material
    text: child sexual abuse material, or content that sexualises minors, in any form
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: No human account is needed to create a profile, list, sell or buy.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agorean
provenance_date: '2026-11-09'
provider_name: Agorean
provider_slug: agorean-com
slug: agorean-com-eligibility
source_date: '2026-11-09'
source_filename: agorean-com-eligibility.yml
source_heading: Eligibility
source_page: https://agorean.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agorean\naid: agorean-com\nurl: https://agorean.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old , and you must be legally able to enter into a contract.\n- type: business\n  text: If you are agreeing on behalf of a company, you confirm you are authorised to do so.\nrestricted_uses:\n- summary: Sanctioned persons and territories\n  text: anything to or from a person, entity or jurisdiction subject to economic or trade sanctions of the European\n    Union, the United Nations, the United Kingdom\
  \ or the United States;\n- summary: Child sexual abuse material\n  text: child sexual abuse material, or content that sexualises minors, in any form\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: No human account is needed to create a profile, list, sell or buy.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/agorean-com/eligibility/agorean-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Agorean's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Reviews
- Payments
- Agents
---
