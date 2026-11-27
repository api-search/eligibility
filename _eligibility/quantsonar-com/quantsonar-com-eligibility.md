---
api_specs:
- filename: quantsonar-com-default-api-openapi.yml
  format: yaml
  label: quantsonar-com 分红送股 API
  slug: quantsonar-com-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quantsonar-com/openapi/quantsonar-com-default-api-openapi.yml
- filename: quantsonar-com-etf-api-openapi.yml
  format: yaml
  label: quantsonar-com ETF API
  slug: quantsonar-com-etf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quantsonar-com/openapi/quantsonar-com-etf-api-openapi.yml
- filename: quantsonar-com-health-api-openapi.yml
  format: yaml
  label: quantsonar-com Health API
  slug: quantsonar-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quantsonar-com/openapi/quantsonar-com-health-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: FREE, PRO and Expert license the individual subscriber to use retrieved data for non-commercial study, research, backtests and personal tools.
    type: individual
  - text: Companies, institutions and other organisations using data in internal commercial systems, business operations or client deliverables must purchase Business and restrict access to the authorised team named in the order.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial use only on individual plans
    text: FREE, PRO and Expert license the individual subscriber to use retrieved data for non-commercial study, research, backtests and personal tools.
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
name: quantsonar-com
provenance_date: '2026-11-10'
provider_name: quantsonar-com
provider_slug: quantsonar-com
slug: quantsonar-com-eligibility
source_date: '2026-11-10'
source_filename: quantsonar-com-eligibility.yml
source_heading: Eligibility
source_page: https://quantsonar.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: quantsonar-com\naid: quantsonar-com\nurl: https://quantsonar.com/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: FREE, PRO and Expert license the individual subscriber to use retrieved data for non-commercial study, research,\n    backtests and personal tools.\n- type: business\n  text: Companies, institutions and other organisations using data in internal commercial systems, business operations\n    or client deliverables must purchase Business and restrict access to the authorised team named in the order.\nrestricted_uses:\n\
  - summary: Non-commercial use only on individual plans\n  text: FREE, PRO and Expert license the individual subscriber to use retrieved data for non-commercial study, research,\n    backtests and personal tools.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/quantsonar-com/eligibility/quantsonar-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from quantsonar-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Data
- China
- Stock Market
---
