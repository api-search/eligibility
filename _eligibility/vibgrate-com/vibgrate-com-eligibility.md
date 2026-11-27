---
api_specs:
- filename: vibgrate-com-openapi-generated.yml
  format: yaml
  label: vibgrate-com API
  slug: vibgrate-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vibgrate-com/openapi/_ae-authored/vibgrate-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If using on behalf of an organization, you have authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the Service for any unlawful purpose or in violation of any applicable laws
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
name: vibgrate-com
provenance_date: '2026-11-10'
provider_name: vibgrate-com
provider_slug: vibgrate-com
slug: vibgrate-com-eligibility
source_date: '2026-11-10'
source_filename: vibgrate-com-eligibility.yml
source_heading: Eligibility
source_page: https://vibgrate.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: vibgrate-com\naid: vibgrate-com\nurl: https://vibgrate.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If using on behalf of an organization, you have authority to bind that organization to these Terms\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the Service for any unlawful purpose or in violation of any applicable laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/vibgrate-com/eligibility/vibgrate-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from vibgrate-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Code-Drift
- Developer Tools
- CI/CD
- Security
---
