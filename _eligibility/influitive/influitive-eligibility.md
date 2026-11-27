---
api_specs:
- filename: influitive-events-api-openapi.yml
  format: yaml
  label: Influitive Events API
  slug: influitive-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/influitive/openapi/influitive-events-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THE COMPANY IDENTIFIED AS THE “CUSTOMER” IN THE ORDER FORM
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitive or benchmarking use
    text: access the Services for purposes of monitoring its availability, performance or functionality, or for any other benchmarking or competitive purpose
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
name: Influitive
provenance_date: '2026-11-09'
provider_name: Influitive
provider_slug: influitive
slug: influitive-eligibility
source_date: '2026-11-09'
source_filename: influitive-eligibility.yml
source_heading: Eligibility
source_page: https://influitive.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Influitive\naid: influitive\nurl: https://influitive.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: THE COMPANY IDENTIFIED AS THE “CUSTOMER” IN THE ORDER FORM\nrestricted_uses:\n- summary: Competitive or benchmarking use\n  text: access the Services for purposes of monitoring its availability, performance or functionality, or for any\n    other benchmarking or competitive purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/influitive/eligibility/influitive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Influitive's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Advocacy
- Customer Community
- Customer Engagement
- Advocacy Marketing
- Referral Marketing
- Customer Loyalty
- Gamification
- Webhook
- Software-as-a-Service
---
