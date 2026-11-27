---
api_specs:
- filename: monkedo-openapi-generated.yml
  format: yaml
  label: Z Yazilim API
  slug: monkedo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monkedo/openapi/_ae-authored/monkedo-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An individual or entity participating in the Program and eligible to earn commissions by promoting Monkedo products.
    type: individual
  minimum_age:
    text: Applicants must be at least 18 years old.
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Anyone wishing to become a Partner must apply to the program.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Z Yazilim
provenance_date: '2026-11-10'
provider_name: Z Yazilim
provider_slug: monkedo
slug: monkedo-eligibility
source_date: '2026-11-10'
source_filename: monkedo-eligibility.yml
source_heading: Eligibility
source_page: https://monkedo.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Z Yazilim\naid: monkedo\nurl: https://monkedo.com/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An individual or entity participating in the Program and eligible to earn commissions by promoting Monkedo\n    products.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Anyone wishing to become a Partner must apply to the program.\nminimum_age:\n  value: '18'\n  text: Applicants must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/monkedo/eligibility/monkedo-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Z Yazilim's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automation
- No-Code
- Integration
- Workflows
---
