---
api_specs:
- filename: oddsrelay-account-api-openapi.yml
  format: yaml
  label: OddsRelay Account API
  slug: oddsrelay-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oddsrelay/openapi/oddsrelay-account-api-openapi.yml
- filename: oddsrelay-discovery-api-openapi.yml
  format: yaml
  label: OddsRelay Discovery API
  slug: oddsrelay-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oddsrelay/openapi/oddsrelay-discovery-api-openapi.yml
- filename: oddsrelay-odds-api-openapi.yml
  format: yaml
  label: OddsRelay Odds API
  slug: oddsrelay-odds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oddsrelay/openapi/oddsrelay-odds-api-openapi.yml
- filename: oddsrelay-service-api-openapi.yml
  format: yaml
  label: OddsRelay Service API
  slug: oddsrelay-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oddsrelay/openapi/oddsrelay-service-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our paid self-serve Plans are for personal use
    type: individual
  - text: A Business needs an Enterprise Order
    type: business
  minimum_age:
    text: You must be 18 or over to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlicensed gambling
    text: will not use the Feed to operate or facilitate unlicensed or unregulated gambling in any jurisdiction where a licence is required
  - summary: Minors and sanctioned jurisdictions
    text: will not provide services to minors or to persons in prohibited or sanctioned jurisdictions
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A Business needs an Enterprise Order
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OddsRelay
provenance_date: '2026-11-10'
provider_name: OddsRelay
provider_slug: oddsrelay
slug: oddsrelay-eligibility
source_date: '2026-11-10'
source_filename: oddsrelay-eligibility.yml
source_heading: Eligibility
source_page: https://oddsrelay.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OddsRelay\naid: oddsrelay\nurl: https://oddsrelay.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Our paid self-serve Plans are for personal use\n- type: business\n  text: A Business needs an Enterprise Order\nrestricted_uses:\n- summary: Unlicensed gambling\n  text: will not use the Feed to operate or facilitate unlicensed or unregulated gambling in any jurisdiction where\n    a licence is required\n- summary: Minors and sanctioned jurisdictions\n  text: will not provide services to minors or to persons in prohibited or sanctioned\
  \ jurisdictions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A Business needs an Enterprise Order\nminimum_age:\n  value: '18'\n  text: You must be 18 or over to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/oddsrelay/eligibility/oddsrelay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from OddsRelay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports Betting
- Odds
- Sports Data
- Matched Betting
- Data Feed
---
