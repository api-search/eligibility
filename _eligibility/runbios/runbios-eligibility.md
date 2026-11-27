---
api_specs:
- filename: runbios-openapi-generated.yml
  format: yaml
  label: UltraSafe AI API
  slug: runbios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runbios/openapi/_ae-authored/runbios-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using Run BiOS on behalf of a company, you confirm you have the authority to accept these terms for that company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harmful model building
    text: Use the platform to build models intended to cause harm, such as malware generation or targeted harassment.
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
name: UltraSafe AI
provenance_date: '2026-11-10'
provider_name: UltraSafe AI
provider_slug: runbios
slug: runbios-eligibility
source_date: '2026-11-10'
source_filename: runbios-eligibility.yml
source_heading: Eligibility
source_page: https://runbios.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UltraSafe AI\naid: runbios\nurl: https://runbios.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using Run BiOS on behalf of a company, you confirm you have the authority to accept these terms\n    for that company.\nrestricted_uses:\n- summary: Harmful model building\n  text: Use the platform to build models intended to cause harm, such as malware generation or targeted harassment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/runbios/eligibility/runbios-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from UltraSafe AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Enterprise
- Platform
- Training
- Inference
---
