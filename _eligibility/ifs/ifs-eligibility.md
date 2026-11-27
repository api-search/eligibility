---
api_specs:
- filename: ifs-finance-api-openapi.yml
  format: yaml
  label: IFS Finance API
  slug: ifs-finance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ifs/openapi/ifs-finance-api-openapi.yml
- filename: ifs-inventory-api-openapi.yml
  format: yaml
  label: IFS Inventory API
  slug: ifs-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ifs/openapi/ifs-inventory-api-openapi.yml
- filename: ifs-procurement-api-openapi.yml
  format: yaml
  label: IFS Procurement API
  slug: ifs-procurement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ifs/openapi/ifs-procurement-api-openapi.yml
- filename: ifs-work-orders-api-openapi.yml
  format: yaml
  label: IFS Work Orders API
  slug: ifs-work-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ifs/openapi/ifs-work-orders-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are agreeing to these Terms and Conditions on behalf of your company
    type: business
  - text: the services are not available to persons who are not legally eligible to be bound by these terms of service
    type: individual
  minimum_age:
    text: you are of the legal age of majority in the jurisdiction in which you reside
    value: legal age of majority
  restricted_uses:
  - summary: Hazardous fail-safe environments
    text: The Services must not be used in any hazardous environments requiring fail safe performance
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
name: IFS
provenance_date: '2026-11-09'
provider_name: IFS
provider_slug: ifs
slug: ifs-eligibility
source_date: '2026-11-09'
source_filename: ifs-eligibility.yml
source_heading: Eligibility
source_page: https://www.ifs.com/en/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: IFS\naid: ifs\nurl: https://www.ifs.com/en/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You are agreeing to these Terms and Conditions on behalf of your company\n- type: individual\n  text: the services are not available to persons who are not legally eligible to be bound by these terms of service\nrestricted_uses:\n- summary: Hazardous fail-safe environments\n  text: The Services must not be used in any hazardous environments requiring fail safe performance\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: legal age of majority\n  text: you are of the legal age of majority in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/ifs/eligibility/ifs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from IFS's own page on 2026-11-09.
synthetic: false
tags:
- ERP
- Field Service Management
- Asset Management
- Manufacturing
- Energy
- Cloud
- Sweden
---
