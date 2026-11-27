---
api_specs:
- filename: aeoess-com-openapi-generated.yml
  format: yaml
  label: aeoess API
  slug: aeoess-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeoess-com/openapi/_ae-authored/aeoess-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may create an account on behalf of yourself
    type: individual
  - text: or a company you represent.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use, sanctions evasion, fraud
    text: You will not use the gateway to issue passports for purposes prohibited by law, to evade sanctions, or to facilitate fraud.
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
name: aeoess
provenance_date: '2026-11-09'
provider_name: aeoess
provider_slug: aeoess-com
slug: aeoess-com-eligibility
source_date: '2026-11-09'
source_filename: aeoess-com-eligibility.yml
source_heading: Eligibility
source_page: https://aeoess.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: aeoess\naid: aeoess-com\nurl: https://aeoess.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may create an account on behalf of yourself\n- type: business\n  text: or a company you represent.\nrestricted_uses:\n- summary: Unlawful use, sanctions evasion, fraud\n  text: You will not use the gateway to issue passports for purposes prohibited by law, to evade sanctions, or to\n    facilitate fraud.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/aeoess-com/eligibility/aeoess-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from aeoess's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Governance
- Open Source
- AgentAuthority
- Platform
---
