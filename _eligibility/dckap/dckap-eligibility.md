---
api_specs:
- filename: dckap-openapi-generated.yml
  format: yaml
  label: DCKAP API
  slug: dckap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dckap/openapi/_ae-authored/dckap-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This Site is controlled, operated and administered by DCKAP from its offices within United States and India. DCKAP makes no representation that materials at this site are appropriate or available for use at other locations outside of United States and India
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export laws
    text: You may not use the Web Site or export the Materials in violation of any applicable export laws and regulations.
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
name: DCKAP
provenance_date: '2026-11-09'
provider_name: DCKAP
provider_slug: dckap
slug: dckap-eligibility
source_date: '2026-11-09'
source_filename: dckap-eligibility.yml
source_heading: Eligibility
source_page: https://www.dckap.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DCKAP\naid: dckap\nurl: https://www.dckap.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This Site is controlled, operated and administered by DCKAP from its offices within United States and India.\n    DCKAP makes no representation that materials at this site are appropriate or available for use at other locations\n    outside of United States and India\nentity_types: []\nrestricted_uses:\n- summary: Export laws\n  text: You may not use the Web Site or export the Materials in violation of any applicable export laws and regulations.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dckap/eligibility/dckap-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from DCKAP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Integration
- ERP
- E-Commerce
- Data Sync
---
