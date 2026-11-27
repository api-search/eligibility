---
api_specs:
- filename: ringahuman-com-openapi-generated.yml
  format: yaml
  label: ringahuman-com API
  slug: ringahuman-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ringahuman-com/openapi/_ae-authored/ringahuman-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited calling uses
    text: Harassment, threats, debt collection, or calls about illegal products or services.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Tasks are dispatched to callers only after we approve the account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ringahuman-com
provenance_date: '2026-11-10'
provider_name: ringahuman-com
provider_slug: ringahuman-com
slug: ringahuman-com-eligibility
source_date: '2026-11-10'
source_filename: ringahuman-com-eligibility.yml
source_heading: Eligibility
source_page: https://ringahuman.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ringahuman-com\naid: ringahuman-com\nurl: https://ringahuman.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited calling uses\n  text: Harassment, threats, debt collection, or calls about illegal products or services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Tasks are dispatched to callers only after we approve the account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ringahuman-com/eligibility/ringahuman-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from ringahuman-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Telephony
- Lead Generation
- Compliance
---
