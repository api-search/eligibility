---
api_specs:
- filename: finology-tech-finology-publicapi-api-openapi.yml
  format: yaml
  label: finology-tech Finology.Public API
  slug: finology-tech-finology-publicapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finology-tech/openapi/finology-tech-finology-publicapi-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This website is intended for individuals who are at least 18 years of age or older and who reside in the United States or territories thereof.
  entity_types:
  - text: This website is intended for individuals who are at least 18 years of age or older and who reside in the United States or territories thereof.
    type: individual
  minimum_age:
    text: at least 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Harassment via loan information
    text: This includes obtaining loan information of others through Finology for the sole purpose of bothering others.
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
name: finology-tech
provenance_date: '2026-11-09'
provider_name: finology-tech
provider_slug: finology-tech
slug: finology-tech-eligibility
source_date: '2026-11-09'
source_filename: finology-tech-eligibility.yml
source_heading: Eligibility
source_page: https://finology.tech/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: finology-tech\naid: finology-tech\nurl: https://finology.tech/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This website is intended for individuals who are at least 18 years of age or older and who reside in the\n    United States or territories thereof.\nentity_types:\n- type: individual\n  text: This website is intended for individuals who are at least 18 years of age or older and who reside in the\n    United States or territories thereof.\nrestricted_uses:\n- summary: Harassment via loan information\n  text: This includes obtaining loan information of\
  \ others through Finology for the sole purpose of bothering others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/finology-tech/eligibility/finology-tech-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from finology-tech's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Student Loans
- AI Integration
- Financial Advisors
---
