---
api_specs:
- filename: zylo-applications-api-openapi.yml
  format: yaml
  label: Zylo Applications API
  slug: zylo-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zylo/openapi/zylo-applications-api-openapi.yml
- filename: zylo-export-jobs-api-openapi.yml
  format: yaml
  label: Zylo Export Jobs API
  slug: zylo-export-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zylo/openapi/zylo-export-jobs-api-openapi.yml
- filename: zylo-import-jobs-api-openapi.yml
  format: yaml
  label: Zylo Import Jobs API
  slug: zylo-import-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zylo/openapi/zylo-import-jobs-api-openapi.yml
- filename: zylo-subscriptions-api-openapi.yml
  format: yaml
  label: Zylo Subscriptions API
  slug: zylo-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zylo/openapi/zylo-subscriptions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: Customer will not permit any User to access or use any Service in a U.S.-embargoed country or region (currently the Crimea, Luhansk or Donetsk regions, Cuba, Iran, North Korea, or Syria)
  entity_types:
  - text: “Customer” means the company stated in the applicable Order Form executed by its personnel and referencing this governing Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-embargoed access
    text: or in violation of any U.S. export law or regulation
  - summary: Competitive development
    text: access the Services to build a competitive product or service
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zylo
provenance_date: '2026-11-10'
provider_name: Zylo
provider_slug: zylo
slug: zylo-eligibility
source_date: '2026-11-10'
source_filename: zylo-eligibility.yml
source_heading: Eligibility
source_page: https://zylo.com/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zylo\naid: zylo\nurl: https://zylo.com/msa\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Customer will not permit any User to access or use any Service in a U.S.-embargoed country or region (currently\n    the Crimea, Luhansk or Donetsk regions, Cuba, Iran, North Korea, or Syria)\nentity_types:\n- type: business\n  text: “Customer” means the company stated in the applicable Order Form executed by its personnel and referencing\n    this governing Agreement.\nrestricted_uses:\n- summary: Export-embargoed access\n  text: or in violation of any U.S. export\
  \ law or regulation\n- summary: Competitive development\n  text: access the Services to build a competitive product or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zylo/eligibility/zylo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Zylo's own page on 2026-11-10.
synthetic: false
tags:
- Budgets
- SaaS Management
- Spend
---
