---
api_specs:
- filename: zammad-openapi-generated.yml
  format: yaml
  label: Zammad API
  slug: zammad-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zammad/openapi/_ae-authored/zammad-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The agreement is intended for entrepreneurs pursuant to § 14 BGB (German Civil Code) and not for consumers pursuant to § 13 BGB.
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
name: Zammad
provenance_date: '2026-11-10'
provider_name: Zammad
provider_slug: zammad
slug: zammad-eligibility
source_date: '2026-11-10'
source_filename: zammad-eligibility.yml
source_heading: Eligibility
source_page: https://zammad.com/en/company/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zammad\naid: zammad\nurl: https://zammad.com/en/company/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The agreement is intended for entrepreneurs pursuant to § 14 BGB (German Civil Code) and not for consumers\n    pursuant to § 13 BGB.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zammad/eligibility/zammad-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Zammad's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Support
- Help Desk
- Artificial Intelligence
- Customer Service
- Platform
---
