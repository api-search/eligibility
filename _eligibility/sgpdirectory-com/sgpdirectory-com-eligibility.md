---
api_specs:
- filename: sgpdirectory-com-api-openapi.json
  format: json
  label: SGP Directory API API
  slug: sgp-directory-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sgpdirectory-com/openapi/_original/sgpdirectory-com-api-openapi.json
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
  - summary: Bulk scraping, spam, fraud, illegal use
    text: Bulk scraping or automated harvesting of data without prior written consent
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
name: sgpdirectory-com
provenance_date: '2026-11-10'
provider_name: sgpdirectory-com
provider_slug: sgpdirectory-com
slug: sgpdirectory-com-eligibility
source_date: '2026-11-10'
source_filename: sgpdirectory-com-eligibility.yml
source_heading: Eligibility
source_page: https://sgpdirectory.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: sgpdirectory-com\naid: sgpdirectory-com\nurl: https://sgpdirectory.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Bulk scraping, spam, fraud, illegal use\n  text: Bulk scraping or automated harvesting of data without prior written consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sgpdirectory-com/eligibility/sgpdirectory-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from sgpdirectory-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Directory
- Singapore
- Business
---
