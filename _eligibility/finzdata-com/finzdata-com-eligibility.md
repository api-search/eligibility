---
api_specs:
- filename: finzdata-com-finzdata-api-openapi.yml
  format: yaml
  label: FinzData API
  slug: finzdata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finzdata-com/openapi/finzdata-com-finzdata-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: use by one individual, for that individual's own personal research and trading only.
    type: individual
  - text: Use for, or on behalf of, any business, fund, firm or employer is commercial use and needs the Institutional plan.
    type: business
  minimum_age:
    text: You must give a valid email address and be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Breach of law
    text: Use the service in breach of any law, including securities and export-control laws.
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
name: FinzData
provenance_date: '2026-11-09'
provider_name: FinzData
provider_slug: finzdata-com
slug: finzdata-com-eligibility
source_date: '2026-11-09'
source_filename: finzdata-com-eligibility.yml
source_heading: Eligibility
source_page: https://finzdata.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FinzData\naid: finzdata-com\nurl: https://finzdata.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: use by one individual, for that individual's own personal research and trading only.\n- type: business\n  text: Use for, or on behalf of, any business, fund, firm or employer is commercial use and needs the Institutional\n    plan.\nrestricted_uses:\n- summary: Breach of law\n  text: Use the service in breach of any law, including securities and export-control laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must give a valid email address and be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/finzdata-com/eligibility/finzdata-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from FinzData's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- Historical Data
- Python
---
