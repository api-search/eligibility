---
api_specs:
- filename: askbase-com-openapi-generated.yml
  format: yaml
  label: AskBase API
  slug: askbase-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askbase-com/openapi/_ae-authored/askbase-com-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: AskBase is a tool for businesses.
    type: business
  minimum_age:
    text: null
    value: null
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
name: AskBase
provenance_date: '2026-11-09'
provider_name: AskBase
provider_slug: askbase-com
slug: askbase-com-eligibility
source_date: '2026-11-09'
source_filename: askbase-com-eligibility.yml
source_heading: Eligibility
source_page: https://askbase.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AskBase\naid: askbase-com\nurl: https://askbase.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: AskBase is a tool for businesses.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/askbase-com/eligibility/askbase-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from AskBase's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Knowledge Base
- Customer Service
- Software-as-a-Service
- Automation
---
