---
api_specs:
- filename: easyparser-com-amazon-api-openapi.yml
  format: yaml
  label: easyparser-com Amazon API
  slug: easyparser-com-amazon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easyparser-com/openapi/easyparser-com-amazon-api-openapi.yml
- filename: easyparser-com-bulk-api-openapi.yml
  format: yaml
  label: easyparser-com Bulk API
  slug: easyparser-com-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easyparser-com/openapi/easyparser-com-bulk-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use Easyparser, you must be at least 18 years old and legally capable of entering into a binding contract.
    type: individual
  minimum_age:
    text: you must be at least 18 years old and legally capable of entering into a binding contract
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: Use the service for illegal or unauthorized purposes
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
name: easyparser-com
provenance_date: '2026-11-09'
provider_name: easyparser-com
provider_slug: easyparser-com
slug: easyparser-com-eligibility
source_date: '2026-11-09'
source_filename: easyparser-com-eligibility.yml
source_heading: Eligibility
source_page: https://easyparser.com/policies/terms-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: easyparser-com\naid: easyparser-com\nurl: https://easyparser.com/policies/terms-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use Easyparser, you must be at least 18 years old and legally capable of entering into a binding contract.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: Use the service for illegal or unauthorized purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old and legally\
  \ capable of entering into a binding contract\n"
source_yaml_url: https://artifacts.apis.io/easyparser-com/eligibility/easyparser-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from easyparser-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Amazon
- Web Scraping
- Real-Time
- Data Extraction
---
