---
api_specs:
- filename: laserfiche-oauth-api-openapi.yml
  format: yaml
  label: Laserfiche OAuth API
  slug: laserfiche-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserfiche/openapi/laserfiche-oauth-api-openapi.yml
- filename: laserfiche-odata4-api-openapi.yml
  format: yaml
  label: Laserfiche Odata4 API
  slug: laserfiche-odata4-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserfiche/openapi/laserfiche-odata4-api-openapi.yml
- filename: laserfiche-repositories-api-openapi.yml
  format: yaml
  label: Laserfiche Repositories API
  slug: laserfiche-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserfiche/openapi/laserfiche-repositories-api-openapi.yml
- filename: laserfiche-repository-api-openapi.yml
  format: yaml
  label: Laserfiche Repository API
  slug: laserfiche-repository-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserfiche/openapi/laserfiche-repository-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Persons who are 18 years or younger, or not of the age of majority, may not use the Site or Services
    value: 18 or younger excluded
  restricted_uses:
  - summary: Export control compliance
    text: You may use our Site and Services only as permitted by applicable law, including export control laws and regulations.
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
name: Laserfiche
provenance_date: '2026-11-09'
provider_name: Laserfiche
provider_slug: laserfiche
slug: laserfiche-eligibility
source_date: '2026-11-09'
source_filename: laserfiche-eligibility.yml
source_heading: Eligibility
source_page: https://www.laserfiche.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Laserfiche\naid: laserfiche\nurl: https://www.laserfiche.com/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control compliance\n  text: You may use our Site and Services only as permitted by applicable law, including export control laws and\n    regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 18 or younger excluded\n  text: Persons who are 18 years or younger, or not of the age of majority, may not use the Site or Services\n"
source_yaml_url: https://artifacts.apis.io/laserfiche/eligibility/laserfiche-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Laserfiche's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise Content Management
- Document Management
- Process Automation
- Artificial Intelligence
---
