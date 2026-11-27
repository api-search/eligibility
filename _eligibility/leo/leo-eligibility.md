---
api_specs:
- filename: leo-prospects-api-openapi.yml
  format: yaml
  label: LeO Public API
  slug: leo-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leo/openapi/leo-prospects-api-openapi.yml
- filename: leo-health-api-openapi.yml
  format: yaml
  label: LeO Health API
  slug: leo-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leo/openapi/leo-health-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents it is not located, organized or resident in a country subject to Sanctions (including but not limited to Cuba, Iran, North Korea, Crimea Region, Russia, Lebanon and Syria).
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No FCRA or credit/insurance underwriting uses of Leads
    text: use the Leads in connection with hard background check purposes, debt collection, credit granting, credit monitoring, account review, collection, insurance underwriting, employment or for any other purpose covered by the Fair Credit Reporting Act
  - summary: No government or defense use of Leads
    text: permit any use of the Leads by governmental agencies, national or state defense and/or intelligence agencies
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
name: LeO
provenance_date: '2026-11-09'
provider_name: LeO
provider_slug: leo
slug: leo-eligibility
source_date: '2026-11-09'
source_filename: leo-eligibility.yml
source_heading: Eligibility
source_page: https://meetleo.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LeO\naid: leo\nurl: https://meetleo.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents it is not located, organized or resident in a country subject to Sanctions (including\n    but not limited to Cuba, Iran, North Korea, Crimea Region, Russia, Lebanon and Syria).\nentity_types: []\nrestricted_uses:\n- summary: No FCRA or credit/insurance underwriting uses of Leads\n  text: use the Leads in connection with hard background check purposes, debt collection, credit granting, credit\n    monitoring, account review, collection, insurance\
  \ underwriting, employment or for any other purpose covered\n    by the Fair Credit Reporting Act\n- summary: No government or defense use of Leads\n  text: permit any use of the Leads by governmental agencies, national or state defense and/or intelligence agencies\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/leo/eligibility/leo-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from LeO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Commercial Insurance
- Property and Casualty
- Employee Benefits
- Insurtech
- Artificial Intelligence
- Sales
- Lead Generation
- Prospecting
- Data Enrichment
- Sales Intelligence
- Non-Profit
- Trucking
- MCP
- Agent-Native
---
