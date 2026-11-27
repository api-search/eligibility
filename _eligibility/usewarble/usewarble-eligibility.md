---
api_specs:
- filename: usewarble-openapi-generated.yml
  format: yaml
  label: Warble API
  slug: usewarble-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewarble/openapi/_ae-authored/usewarble-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Warble is for businesses in the United States. If you are outside the United States, do not sign up.
  minimum_age:
    text: You are at least 18 years old and have the legal capacity to enter into a contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful content
    text: Breaks the law — anything unlawful where you are, where we are, or where the content is published.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may decline to open an account for anyone, for any reason the law allows.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Warble
provenance_date: '2026-11-10'
provider_name: Warble
provider_slug: usewarble
slug: usewarble-eligibility
source_date: '2026-11-10'
source_filename: usewarble-eligibility.yml
source_heading: Eligibility
source_page: https://usewarble.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Warble\naid: usewarble\nurl: https://usewarble.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Warble is for businesses in the United States. If you are outside the United States, do not sign up.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful content\n  text: Breaks the law — anything unlawful where you are, where we are, or where the content is published.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may decline to open an account for anyone, for any reason the law allows.\nminimum_age:\n  value: '18'\n  text: You are at\
  \ least 18 years old and have the legal capacity to enter into a contract.\n"
source_yaml_url: https://artifacts.apis.io/usewarble/eligibility/usewarble-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Warble's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Social Media
- Small Business
- Automation
---
