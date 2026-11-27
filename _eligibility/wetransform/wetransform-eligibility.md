---
api_specs:
- filename: wetransform-openapi-generated.yml
  format: yaml
  label: WeTransform API
  slug: wetransform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wetransform/openapi/_ae-authored/wetransform-openapi-generated.yml
claim_count: 1
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
  - summary: Unlawful, harmful, or disruptive use of website
    text: You may not use our website in any way that causes, or may cause, damage to the website or impairment of the availability or accessibility of the website; or in any way which is unlawful, illegal, fraudulent or harmful
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
name: WeTransform
provenance_date: '2026-11-10'
provider_name: WeTransform
provider_slug: wetransform
slug: wetransform-eligibility
source_date: '2026-11-10'
source_filename: wetransform-eligibility.yml
source_heading: Eligibility
source_page: https://wetransform.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WeTransform\naid: wetransform\nurl: https://wetransform.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, harmful, or disruptive use of website\n  text: You may not use our website in any way that causes, or may cause, damage to the website or impairment of\n    the availability or accessibility of the website; or in any way which is unlawful, illegal, fraudulent or harmful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wetransform/eligibility/wetransform-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from WeTransform's own page on 2026-11-10.
synthetic: false
tags:
- Data Integration
- B2B SaaS
- No-Code
- Artificial Intelligence
- Embedded Import
---
