---
api_specs:
- filename: leadgenius-campaigns-api-openapi.yml
  format: yaml
  label: LeadGenius Campaigns API
  slug: leadgenius-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadgenius/openapi/leadgenius-campaigns-api-openapi.yml
- filename: leadgenius-exclusion-api-openapi.yml
  format: yaml
  label: LeadGenius Exclusion API
  slug: leadgenius-exclusion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadgenius/openapi/leadgenius-exclusion-api-openapi.yml
- filename: leadgenius-rapid-enrichment-api-openapi.yml
  format: yaml
  label: LeadGenius Rapid Enrichment API
  slug: leadgenius-rapid-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadgenius/openapi/leadgenius-rapid-enrichment-api-openapi.yml
- filename: leadgenius-records-api-openapi.yml
  format: yaml
  label: LeadGenius Records API
  slug: leadgenius-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadgenius/openapi/leadgenius-records-api-openapi.yml
- filename: leadgenius-usage-api-openapi.yml
  format: yaml
  label: LeadGenius Usage API
  slug: leadgenius-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadgenius/openapi/leadgenius-usage-api-openapi.yml
- filename: leadgenius-leadgenius-enrichment-api-api-openapi.yml
  format: yaml
  label: LeadGenius Enrichment API
  slug: leadgenius-leadgenius-enrichment-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadgenius/openapi/leadgenius-leadgenius-enrichment-api-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 13, you are not authorized to use the Service.
    value: '13'
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
name: LeadGenius
provenance_date: '2026-11-09'
provider_name: LeadGenius
provider_slug: leadgenius
slug: leadgenius-eligibility
source_date: '2026-11-09'
source_filename: leadgenius-eligibility.yml
source_heading: Eligibility
source_page: https://www.leadgenius.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LeadGenius\naid: leadgenius\nurl: https://www.leadgenius.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13, you are not authorized to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/leadgenius/eligibility/leadgenius-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from LeadGenius's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Enrichment
- Lead Generation
- Sales
- Marketing
- B2B Data
- Contact Data
- Firmographics
- Go-To-Market
- Account Based Marketing
---
