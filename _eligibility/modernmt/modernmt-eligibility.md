---
api_specs:
- filename: modernmt-openapi-generated.yml
  format: yaml
  label: ModernMT API
  slug: modernmt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modernmt/openapi/_ae-authored/modernmt-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is dedicated exclusively to companies and professionals, meaning natural or legal persons acting in the exercise of their business, commercial or professional activity.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to open an Account on the Platform and use the Service.
    value: '18'
  restricted_uses:
  - summary: Consumers excluded
    text: consumers, i.e. natural persons acting for purposes unrelated to such activities, are not included among the recipients of the Service.
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
name: ModernMT
provenance_date: '2026-11-10'
provider_name: ModernMT
provider_slug: modernmt
slug: modernmt-eligibility
source_date: '2026-11-10'
source_filename: modernmt-eligibility.yml
source_heading: Eligibility
source_page: https://www.modernmt.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ModernMT\naid: modernmt\nurl: https://www.modernmt.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is dedicated exclusively to companies and professionals, meaning natural or legal persons acting\n    in the exercise of their business, commercial or professional activity.\nrestricted_uses:\n- summary: Consumers excluded\n  text: consumers, i.e. natural persons acting for purposes unrelated to such activities, are not included among\n    the recipients of the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to open an Account on the Platform and use the Service.\n"
source_yaml_url: https://artifacts.apis.io/modernmt/eligibility/modernmt-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ModernMT's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Translation
- Multilingual
---
