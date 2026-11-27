---
api_specs:
- filename: compsapi-com-comps-api-openapi.yml
  format: yaml
  label: compsapi-com Comps API
  slug: compsapi-com-comps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsapi-com/openapi/compsapi-com-comps-api-openapi.yml
- filename: compsapi-com-health-api-openapi.yml
  format: yaml
  label: compsapi-com Health API
  slug: compsapi-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsapi-com/openapi/compsapi-com-health-api-openapi.yml
- filename: compsapi-com-sold-api-openapi.yml
  format: yaml
  label: compsapi-com Sold API
  slug: compsapi-com-sold-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsapi-com/openapi/compsapi-com-sold-api-openapi.yml
- filename: compsapi-com-usage-api-openapi.yml
  format: yaml
  label: compsapi-com Usage API
  slug: compsapi-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsapi-com/openapi/compsapi-com-usage-api-openapi.yml
claim_count: 2
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
  - summary: Unlawful use
    text: use the data for anything unlawful
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need a Google account to sign in.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: compsapi-com
provenance_date: '2026-11-09'
provider_name: compsapi-com
provider_slug: compsapi-com
slug: compsapi-com-eligibility
source_date: '2026-11-09'
source_filename: compsapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://compsapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: compsapi-com\naid: compsapi-com\nurl: https://compsapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: use the data for anything unlawful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need a Google account to sign in.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/compsapi-com/eligibility/compsapi-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from compsapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- eBay
- Data
- Pricing
- Marketplace
---
