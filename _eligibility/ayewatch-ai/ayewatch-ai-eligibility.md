---
api_specs:
- filename: ayewatch-ai-openapi-generated.yml
  format: yaml
  label: Ayewatch API
  slug: ayewatch-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayewatch-ai/openapi/_ae-authored/ayewatch-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Competitors barred
    text: You may not use the Service if you are a competitor of ours
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
name: Ayewatch
provenance_date: '2026-11-09'
provider_name: Ayewatch
provider_slug: ayewatch-ai
slug: ayewatch-ai-eligibility
source_date: '2026-11-09'
source_filename: ayewatch-ai-eligibility.yml
source_heading: Eligibility
source_page: https://ayewatch.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ayewatch\naid: ayewatch-ai\nurl: https://ayewatch.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization to these Terms\nrestricted_uses:\n- summary: Competitors barred\n  text: You may not use the Service if you are a competitor of ours\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to\
  \ use the Service.\n"
source_yaml_url: https://artifacts.apis.io/ayewatch-ai/eligibility/ayewatch-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ayewatch's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Monitoring
- Real-Time
- Webhook
- Dashboards
- News
---
