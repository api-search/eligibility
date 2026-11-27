---
api_specs:
- filename: arena-predictions-com-api-keys-api-openapi.yml
  format: yaml
  label: Arena API keys API
  slug: arena-predictions-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-api-keys-api-openapi.yml
- filename: arena-predictions-com-identity-api-openapi.yml
  format: yaml
  label: Arena Identity API
  slug: arena-predictions-com-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-identity-api-openapi.yml
- filename: arena-predictions-com-markets-api-openapi.yml
  format: yaml
  label: Arena Markets API
  slug: arena-predictions-com-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-markets-api-openapi.yml
- filename: arena-predictions-com-portfolio-api-openapi.yml
  format: yaml
  label: Arena Portfolio API
  slug: arena-predictions-com-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-portfolio-api-openapi.yml
- filename: arena-predictions-com-records-api-openapi.yml
  format: yaml
  label: Arena Records API
  slug: arena-predictions-com-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-records-api-openapi.yml
- filename: arena-predictions-com-status-api-openapi.yml
  format: yaml
  label: Arena Status API
  slug: arena-predictions-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-status-api-openapi.yml
- filename: arena-predictions-com-trading-api-openapi.yml
  format: yaml
  label: Arena Trading API
  slug: arena-predictions-com-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-trading-api-openapi.yml
- filename: arena-predictions-com-usage-api-openapi.yml
  format: yaml
  label: Arena Usage API
  slug: arena-predictions-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-usage-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country subject to a U.S. Government embargo or designated as terrorist-supporting, and that you are not on any U.S. Government list of prohibited or restricted parties.
  entity_types:
  - text: You must be at least 17 years of age to use Arena. By using Arena, you represent that you meet this requirement and that you are able to form a binding contract with us.
    type: individual
  minimum_age:
    text: You must be at least 17 years of age to use Arena.
    value: '17'
  restricted_uses:
  - summary: Not for real-world financial or wagering decisions
    text: Do not rely on Arena for real-world financial or wagering decisions.
  - summary: Unlawful or harmful use
    text: use Arena for any unlawful, deceptive, or harmful purpose
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
name: Arena
provenance_date: '2026-11-09'
provider_name: Arena
provider_slug: arena-predictions-com
slug: arena-predictions-com-eligibility
source_date: '2026-11-09'
source_filename: arena-predictions-com-eligibility.yml
source_heading: Eligibility
source_page: https://arena-predictions.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arena\naid: arena-predictions-com\nurl: https://arena-predictions.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country subject to a U.S. Government embargo or designated as\n    terrorist-supporting, and that you are not on any U.S. Government list of prohibited or restricted parties.\nentity_types:\n- type: individual\n  text: You must be at least 17 years of age to use Arena. By using Arena, you represent that you meet this requirement\n    and that you are able to form a binding contract with us.\nrestricted_uses:\n- summary:\
  \ Not for real-world financial or wagering decisions\n  text: Do not rely on Arena for real-world financial or wagering decisions.\n- summary: Unlawful or harmful use\n  text: use Arena for any unlawful, deceptive, or harmful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '17'\n  text: You must be at least 17 years of age to use Arena.\n"
source_yaml_url: https://artifacts.apis.io/arena-predictions-com/eligibility/arena-predictions-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Arena's own page on 2026-11-09.
synthetic: false
tags:
- Prediction Markets
- Paper Trading
- Sandbox
- CLI
---
