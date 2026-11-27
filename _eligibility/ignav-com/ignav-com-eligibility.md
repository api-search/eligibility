---
api_specs:
- filename: ignav-com-airports-api-openapi.yml
  format: yaml
  label: ignav-com Airports API
  slug: ignav-com-airports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ignav-com/openapi/ignav-com-airports-api-openapi.yml
- filename: ignav-com-fares-api-openapi.yml
  format: yaml
  label: ignav-com Fares API
  slug: ignav-com-fares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ignav-com/openapi/ignav-com-fares-api-openapi.yml
- filename: ignav-com-health-api-openapi.yml
  format: yaml
  label: ignav-com Health API
  slug: ignav-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ignav-com/openapi/ignav-com-health-api-openapi.yml
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
  - summary: Unlawful use or third-party rights violation
    text: You may not reverse engineer the Service, resell raw API access, or use it to violate any law or third-party right.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate information when creating an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ignav-com
provenance_date: '2026-11-09'
provider_name: ignav-com
provider_slug: ignav-com
slug: ignav-com-eligibility
source_date: '2026-11-09'
source_filename: ignav-com-eligibility.yml
source_heading: Eligibility
source_page: https://ignav.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ignav-com\naid: ignav-com\nurl: https://ignav.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use or third-party rights violation\n  text: You may not reverse engineer the Service, resell raw API access, or use it to violate any law or third-party\n    right.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide accurate information when creating an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ignav-com/eligibility/ignav-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from ignav-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Flights
- Travel
- Pricing
- Data
---
