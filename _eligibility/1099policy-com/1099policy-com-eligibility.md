---
api_specs:
- filename: 1099policy-com-openapi-generated.yml
  format: yaml
  label: 1099policy-com API
  slug: 1099policy-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1099policy-com/openapi/_ae-authored/1099policy-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are over the age of 18, as the Services are not intended for children under 18
    value: '18'
  restricted_uses:
  - summary: Intended purpose only
    text: the Platform will only be used for intended purpose as described in these Terms
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
name: 1099policy-com
provenance_date: '2026-11-09'
provider_name: 1099policy-com
provider_slug: 1099policy-com
slug: 1099policy-com-eligibility
source_date: '2026-11-09'
source_filename: 1099policy-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.1099policy.com/terms/licensee
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1099policy-com\naid: 1099policy-com\nurl: https://www.1099policy.com/terms/licensee\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Intended purpose only\n  text: the Platform will only be used for intended purpose as described in these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are over the age of 18, as the Services are not intended for children under 18\n"
source_yaml_url: https://artifacts.apis.io/1099policy-com/eligibility/1099policy-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from 1099policy-com's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Compliance
- Contractors
- Workers Comp
---
