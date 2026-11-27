---
api_specs:
- filename: als-global-preference-api-openapi.yml
  format: yaml
  label: ALS Preference API
  slug: als-global-preference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/als-global/openapi/als-global-preference-api-openapi.yml
- filename: als-global-sample-api-openapi.yml
  format: yaml
  label: ALS Sample API
  slug: als-global-sample-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/als-global/openapi/als-global-sample-api-openapi.yml
- filename: als-global-search-api-openapi.yml
  format: yaml
  label: ALS Search API
  slug: als-global-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/als-global/openapi/als-global-search-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited uses of the Site
    text: 'You agree not to use the Site: in any way that violates any applicable federal, state, local or international law or regulation'
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
name: ALS
provenance_date: '2026-11-09'
provider_name: ALS
provider_slug: als-global
slug: als-global-eligibility
source_date: '2026-11-09'
source_filename: als-global-eligibility.yml
source_heading: Eligibility
source_page: https://www.alsglobal.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ALS\naid: als-global\nurl: https://www.alsglobal.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses of the Site\n  text: 'You agree not to use the Site: in any way that violates any applicable federal, state, local or international\n    law or regulation'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/als-global/eligibility/als-global-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ALS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Laboratory Testing
- Environmental Testing
- Inspection
- Certification
- Geochemistry
- Food Testing
- LIMS Integration
---
