---
api_specs:
- filename: zego-customer-integration-api-openapi.yml
  format: yaml
  label: Zego Customer Integration API
  slug: zego-customer-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zego/openapi/zego-customer-integration-api-openapi.yml
- filename: zego-customers-api-openapi.yml
  format: yaml
  label: Zego Customers API
  slug: zego-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zego/openapi/zego-customers-api-openapi.yml
- filename: zego-occupations-api-openapi.yml
  format: yaml
  label: Zego Occupations API
  slug: zego-occupations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zego/openapi/zego-occupations-api-openapi.yml
- filename: zego-policies-api-openapi.yml
  format: yaml
  label: Zego Policies API
  slug: zego-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zego/openapi/zego-policies-api-openapi.yml
- filename: zego-shifts-api-openapi.yml
  format: yaml
  label: Zego Shifts API
  slug: zego-shifts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zego/openapi/zego-shifts-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Region 🇬🇧 United Kingdom
  minimum_age:
    text: null
    value: null
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
name: Zego
provenance_date: '2026-11-10'
provider_name: Zego
provider_slug: zego
slug: zego-eligibility
source_date: '2026-11-10'
source_filename: zego-eligibility.yml
source_heading: Eligibility
source_page: https://www.zego.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zego\naid: zego\nurl: https://www.zego.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Region \U0001F1EC\U0001F1E7 United Kingdom\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zego/eligibility/zego-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Zego's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Auto Insurance
- Gig Economy
- Telematics
- Fleet Insurance
- Public Liability
- Partner API
---
