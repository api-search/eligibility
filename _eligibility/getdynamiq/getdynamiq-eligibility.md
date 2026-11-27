---
api_specs:
- filename: getdynamiq-api-reference-openapi-generated.yml
  format: yaml
  label: Dynamiq API Reference API
  slug: api-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getdynamiq/openapi/_ae-authored/getdynamiq-api-reference-openapi-generated.yml
- filename: getdynamiq-platform-openapi-generated.yml
  format: yaml
  label: Dynamiq Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getdynamiq/openapi/_ae-authored/getdynamiq-platform-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Client" , "you," or "your" refers to the organization or individual using the Services.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: PHI use requires BAA
    text: If you are subject to the Health Insurance Portability and Accountability Act of 1996 ("HIPAA") and use our Services in a manner that involves PHI, we agree to enter into a separate Business Associate Agreement ("BAA").
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
name: Dynamiq
provenance_date: '2026-11-09'
provider_name: Dynamiq
provider_slug: getdynamiq
slug: getdynamiq-eligibility
source_date: '2026-11-09'
source_filename: getdynamiq-eligibility.yml
source_heading: Eligibility
source_page: https://www.getdynamiq.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dynamiq\naid: getdynamiq\nurl: https://www.getdynamiq.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: '\"Client\" , \"you,\" or \"your\" refers to the organization or individual using the Services.'\nrestricted_uses:\n- summary: PHI use requires BAA\n  text: If you are subject to the Health Insurance Portability and Accountability Act of 1996 (\"HIPAA\") and use\n    our Services in a manner that involves PHI, we agree to enter into a separate Business Associate Agreement (\"BAA\").\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/getdynamiq/eligibility/getdynamiq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Dynamiq's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Enterprise
- Platform
- Agents
---
