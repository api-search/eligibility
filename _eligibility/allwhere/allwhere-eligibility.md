---
api_specs:
- filename: allwhere-openapi-generated.yml
  format: yaml
  label: Allwhere API
  slug: allwhere-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allwhere/openapi/_ae-authored/allwhere-openapi-generated.yml
- filename: allwhere-beta-api-openapi.yml
  format: yaml
  label: allwhere Beta API
  slug: allwhere-beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allwhere/openapi/allwhere-beta-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Service is not intended for use by anyone under 18 years of age.
    value: '18'
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
name: allwhere
provenance_date: '2026-11-09'
provider_name: allwhere
provider_slug: allwhere
slug: allwhere-eligibility
source_date: '2026-11-09'
source_filename: allwhere-eligibility.yml
source_heading: Eligibility
source_page: https://www.allwhere.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: allwhere\naid: allwhere\nurl: https://www.allwhere.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is not intended for use by anyone under 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/allwhere/eligibility/allwhere-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from allwhere's own page on 2026-11-09.
synthetic: false
tags:
- Company
- IT
- Asset Management
- Procurement
- Remote-Workforce
- Enterprise
---
