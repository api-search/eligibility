---
api_specs:
- filename: thalium-openapi-generated.yml
  format: yaml
  label: SYSGRAFT API
  slug: thalium-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thalium/openapi/_ae-authored/thalium-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to create an account.
    type: individual
  - text: If you are accepting these Terms on behalf of an organisation, you represent that you have authority to bind that organisation.
    type: business
  minimum_age:
    text: You must be at least 18 years old to create an account.
    value: '18'
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
name: SYSGRAFT
provenance_date: '2026-11-10'
provider_name: SYSGRAFT
provider_slug: thalium
slug: thalium-eligibility
source_date: '2026-11-10'
source_filename: thalium-eligibility.yml
source_heading: Eligibility
source_page: https://thalium.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SYSGRAFT\naid: thalium\nurl: https://thalium.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to create an account.\n- type: business\n  text: If you are accepting these Terms on behalf of an organisation, you represent that you have authority to\n    bind that organisation.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/thalium/eligibility/thalium-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from SYSGRAFT's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Privacy
- Memory API
- Orchestration
---
