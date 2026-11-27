---
api_specs:
- filename: broadridge-accounts-api-openapi.yml
  format: yaml
  label: broadridge Accounts API
  slug: broadridge-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broadridge/openapi/broadridge-accounts-api-openapi.yml
- filename: broadridge-performance-api-openapi.yml
  format: yaml
  label: broadridge Performance API
  slug: broadridge-performance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broadridge/openapi/broadridge-performance-api-openapi.yml
- filename: broadridge-positions-api-openapi.yml
  format: yaml
  label: broadridge Positions API
  slug: broadridge-positions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broadridge/openapi/broadridge-positions-api-openapi.yml
- filename: broadridge-transactions-api-openapi.yml
  format: yaml
  label: broadridge Transactions API
  slug: broadridge-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broadridge/openapi/broadridge-transactions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting on behalf of someone else, you represent and warrant that you have full legal authority to bind that person or entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Noncommercial use only
    text: You agree to use any Site and the Site Content solely for your own noncommercial use and benefit.
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
name: Broadridge
provenance_date: '2026-11-09'
provider_name: Broadridge
provider_slug: broadridge
slug: broadridge-eligibility
source_date: '2026-11-09'
source_filename: broadridge-eligibility.yml
source_heading: Eligibility
source_page: https://www.broadridge.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Broadridge\naid: broadridge\nurl: https://www.broadridge.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting on behalf of someone else, you represent and warrant that you have full legal authority\n    to bind that person or entity to these Terms.\nrestricted_uses:\n- summary: Noncommercial use only\n  text: You agree to use any Site and the Site Content solely for your own noncommercial use and benefit.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/broadridge/eligibility/broadridge-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Broadridge's own page on 2026-11-09.
synthetic: false
tags:
- Fortune 1000
- Wealth Management
---
