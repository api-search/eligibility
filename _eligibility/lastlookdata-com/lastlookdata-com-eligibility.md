---
api_specs:
- filename: lastlookdata-com-openapi.json
  format: json
  label: LastLook Data API
  slug: lastlook-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastlookdata-com/openapi/lastlookdata-com-openapi.json
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
  - summary: No unlicensed financial advice
    text: Use the service to provide financial advice or investment recommendations without appropriate disclosures and licenses.
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
name: lastlookdata-com
provenance_date: '2026-11-09'
provider_name: lastlookdata-com
provider_slug: lastlookdata-com
slug: lastlookdata-com-eligibility
source_date: '2026-11-09'
source_filename: lastlookdata-com-eligibility.yml
source_heading: Eligibility
source_page: https://lastlookdata.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: lastlookdata-com\naid: lastlookdata-com\nurl: https://lastlookdata.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No unlicensed financial advice\n  text: Use the service to provide financial advice or investment recommendations without appropriate disclosures\n    and licenses.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lastlookdata-com/eligibility/lastlookdata-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from lastlookdata-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Data
- Artificial Intelligence
- Market Data
---
