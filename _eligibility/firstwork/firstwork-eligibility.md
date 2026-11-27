---
api_specs:
- filename: firstwork-openapi-generated.yml
  format: yaml
  label: Firstwork API
  slug: firstwork-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firstwork/openapi/_ae-authored/firstwork-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Users must be at least 18 years old to use our services.
    value: '18'
  restricted_uses:
  - summary: Harmful, fraudulent, or illegal activity
    text: Users are prohibited from engaging in any activity that is harmful, fraudulent, or illegal while using our services.
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
name: Firstwork
provenance_date: '2026-11-09'
provider_name: Firstwork
provider_slug: firstwork
slug: firstwork-eligibility
source_date: '2026-11-09'
source_filename: firstwork-eligibility.yml
source_heading: Eligibility
source_page: https://www.firstwork.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Firstwork\naid: firstwork\nurl: https://www.firstwork.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harmful, fraudulent, or illegal activity\n  text: Users are prohibited from engaging in any activity that is harmful, fraudulent, or illegal while using our\n    services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users must be at least 18 years old to use our services.\n"
source_yaml_url: https://artifacts.apis.io/firstwork/eligibility/firstwork-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Firstwork's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Human Resources
- Frontline
- Automation
- Compliance
---
