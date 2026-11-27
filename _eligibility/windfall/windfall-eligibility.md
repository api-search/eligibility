---
api_specs:
- filename: windfall-windfall-api-api-openapi.yml
  format: yaml
  label: Windfall API
  slug: windfall-windfall-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/windfall/openapi/windfall-windfall-api-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are provided for access and use only by persons located in the United States.
  entity_types:
  - text: if an individual, are at least 18 years of age
    type: individual
  - text: If you are entering into this Agreement on behalf of an entity, you represent that you have the authority to bind such entity to this Agreement.
    type: business
  minimum_age:
    text: if an individual, are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Benchmarking or competitive monitoring
    text: will not access the Services to monitor their availability, functionality, or for any other benchmarking or competitive purposes
  - summary: Uploading sensitive personal information
    text: You are prohibited from uploading any “sensitive” personally identifiable information to the Services
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
name: Windfall
provenance_date: '2026-11-10'
provider_name: Windfall
provider_slug: windfall
slug: windfall-eligibility
source_date: '2026-11-10'
source_filename: windfall-eligibility.yml
source_heading: Eligibility
source_page: https://www.windfall.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Windfall\naid: windfall\nurl: https://www.windfall.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are provided for access and use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: if an individual, are at least 18 years of age\n- type: business\n  text: If you are entering into this Agreement on behalf of an entity, you represent that you have the authority\n    to bind such entity to this Agreement.\nrestricted_uses:\n- summary: Benchmarking or competitive monitoring\n  text: will not access the Services\
  \ to monitor their availability, functionality, or for any other benchmarking\n    or competitive purposes\n- summary: Uploading sensitive personal information\n  text: You are prohibited from uploading any “sensitive” personally identifiable information to the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if an individual, are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/windfall/eligibility/windfall-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Windfall's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Data Enrichment
- Wealth Data
- People Intelligence
- Career Data
- Identity Resolution
- Sales Intelligence
- Marketing
- Data
- Net Worth
- Sales
---
