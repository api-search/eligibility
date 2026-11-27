---
api_specs:
- filename: calcfleet-com-ai-api-openapi.yml
  format: yaml
  label: CalcFleet AI API
  slug: calcfleet-com-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-ai-api-openapi.yml
- filename: calcfleet-com-auto-api-openapi.yml
  format: yaml
  label: CalcFleet Auto API
  slug: calcfleet-com-auto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-auto-api-openapi.yml
- filename: calcfleet-com-business-api-openapi.yml
  format: yaml
  label: CalcFleet Business API
  slug: calcfleet-com-business-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-business-api-openapi.yml
- filename: calcfleet-com-cooking-api-openapi.yml
  format: yaml
  label: CalcFleet Cooking API
  slug: calcfleet-com-cooking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-cooking-api-openapi.yml
- filename: calcfleet-com-debt-api-openapi.yml
  format: yaml
  label: CalcFleet Debt API
  slug: calcfleet-com-debt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-debt-api-openapi.yml
- filename: calcfleet-com-fitness-api-openapi.yml
  format: yaml
  label: CalcFleet Fitness API
  slug: calcfleet-com-fitness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-fitness-api-openapi.yml
- filename: calcfleet-com-freelance-api-openapi.yml
  format: yaml
  label: CalcFleet Freelance API
  slug: calcfleet-com-freelance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-freelance-api-openapi.yml
- filename: calcfleet-com-home-api-openapi.yml
  format: yaml
  label: CalcFleet Home API
  slug: calcfleet-com-home-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-home-api-openapi.yml
- filename: calcfleet-com-loans-api-openapi.yml
  format: yaml
  label: CalcFleet Loans API
  slug: calcfleet-com-loans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-loans-api-openapi.yml
- filename: calcfleet-com-mortgage-api-openapi.yml
  format: yaml
  label: CalcFleet Mortgage API
  slug: calcfleet-com-mortgage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-mortgage-api-openapi.yml
- filename: calcfleet-com-pet-api-openapi.yml
  format: yaml
  label: CalcFleet Pet API
  slug: calcfleet-com-pet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-pet-api-openapi.yml
- filename: calcfleet-com-photography-api-openapi.yml
  format: yaml
  label: CalcFleet Photography API
  slug: calcfleet-com-photography-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-photography-api-openapi.yml
- filename: calcfleet-com-pro-api-openapi.yml
  format: yaml
  label: CalcFleet Pro API
  slug: calcfleet-com-pro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-pro-api-openapi.yml
- filename: calcfleet-com-salary-api-openapi.yml
  format: yaml
  label: CalcFleet Salary API
  slug: calcfleet-com-salary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-salary-api-openapi.yml
- filename: calcfleet-com-savings-api-openapi.yml
  format: yaml
  label: CalcFleet Savings API
  slug: calcfleet-com-savings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-savings-api-openapi.yml
- filename: calcfleet-com-sport-api-openapi.yml
  format: yaml
  label: CalcFleet Sport API
  slug: calcfleet-com-sport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calcfleet-com/openapi/calcfleet-com-sport-api-openapi.yml
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
  - summary: Not professional advice
    text: Nothing here constitutes financial, investment, tax, legal, medical, or other professional advice.
  - summary: Do not use where harm could result
    text: do not use it where errors or downtime could cause material harm.
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
name: CalcFleet
provenance_date: '2026-11-09'
provider_name: CalcFleet
provider_slug: calcfleet-com
slug: calcfleet-com-eligibility
source_date: '2026-11-09'
source_filename: calcfleet-com-eligibility.yml
source_heading: Eligibility
source_page: https://calcfleet.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CalcFleet\naid: calcfleet-com\nurl: https://calcfleet.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not professional advice\n  text: Nothing here constitutes financial, investment, tax, legal, medical, or other professional advice.\n- summary: Do not use where harm could result\n  text: do not use it where errors or downtime could cause material harm.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/calcfleet-com/eligibility/calcfleet-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from CalcFleet's own page on 2026-11-09.
synthetic: false
tags:
- Calculator
- Artificial Intelligence
- VCC
- Free
---
