---
api_specs:
- filename: blackflagalert-com-api-openapi.json
  format: json
  label: Black Flag Alert Open API v2 API
  slug: black-flag-alert-open-api-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackflagalert-com/openapi/_original/blackflagalert-com-api-openapi.json
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: aggregates Public Records... on companies registered in England & Wales
  entity_types:
  - text: if you are using the Service on behalf of an organisation, you have authority to bind that organisation to these terms
    type: business
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Automated legal decisions without human review
    text: use the Service to make automated decisions producing legal effects on individuals without independent human review
  - summary: Unlawful purposes
    text: use the Service for any unlawful purpose, including stalking, harassment, or doxxing of natural persons
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may, at our sole discretion, refuse to create an Account, or suspend or terminate any Account, for any User who breaches these terms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Black Flag Alert
provenance_date: '2026-11-09'
provider_name: Black Flag Alert
provider_slug: blackflagalert-com
slug: blackflagalert-com-eligibility
source_date: '2026-11-09'
source_filename: blackflagalert-com-eligibility.yml
source_heading: Eligibility
source_page: https://blackflagalert.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Black Flag Alert\naid: blackflagalert-com\nurl: https://blackflagalert.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: aggregates Public Records... on companies registered in England & Wales\nentity_types:\n- type: business\n  text: if you are using the Service on behalf of an organisation, you have authority to bind that organisation\n    to these terms\nrestricted_uses:\n- summary: Automated legal decisions without human review\n  text: use the Service to make automated decisions producing legal effects on individuals without independent human\n    review\n- summary:\
  \ Unlawful purposes\n  text: use the Service for any unlawful purpose, including stalking, harassment, or doxxing of natural persons\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may, at our sole discretion, refuse to create an Account, or suspend or terminate any Account, for any\n    User who breaches these terms.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/blackflagalert-com/eligibility/blackflagalert-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Black Flag Alert's own page on 2026-11-09.
synthetic: false
tags:
- Credit Intelligence
- Company Data
- Risk Scoring
- UK Companies
- Financial Services
---
