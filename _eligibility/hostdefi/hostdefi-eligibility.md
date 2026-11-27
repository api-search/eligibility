---
api_specs:
- filename: hostdefi-token-risk-api-openapi.yml
  format: yaml
  label: HostDeFi Token Risk API
  slug: hostdefi-token-risk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hostdefi/openapi/hostdefi-token-risk-api-openapi.yml
- filename: hostdefi-analyze-token-api-openapi.yml
  format: yaml
  label: HostDeFi Analyze Token API
  slug: hostdefi-analyze-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hostdefi/openapi/hostdefi-analyze-token-api-openapi.yml
- filename: hostdefi-health-api-openapi.yml
  format: yaml
  label: HostDeFi Health API
  slug: hostdefi-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hostdefi/openapi/hostdefi-health-api-openapi.yml
- filename: hostdefi-keys-api-openapi.yml
  format: yaml
  label: HostDeFi Keys API
  slug: hostdefi-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hostdefi/openapi/hostdefi-keys-api-openapi.yml
- filename: hostdefi-scan-api-openapi.yml
  format: yaml
  label: HostDeFi Scan API
  slug: hostdefi-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hostdefi/openapi/hostdefi-scan-api-openapi.yml
- filename: hostdefi-usage-api-openapi.yml
  format: yaml
  label: HostDeFi Usage API
  slug: hostdefi-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hostdefi/openapi/hostdefi-usage-api-openapi.yml
- filename: hostdefi-x402-machine-payable-api-openapi.yml
  format: yaml
  label: HostDeFi x402 (machine-payable) API
  slug: hostdefi-x402-machine-payable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hostdefi/openapi/hostdefi-x402-machine-payable-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access from comprehensively sanctioned jurisdictions is prohibited where prohibited by applicable law.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned jurisdictions
    text: Access from comprehensively sanctioned jurisdictions is prohibited where prohibited by applicable law.
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
name: HostDeFi
provenance_date: '2026-11-09'
provider_name: HostDeFi
provider_slug: hostdefi
slug: hostdefi-eligibility
source_date: '2026-11-09'
source_filename: hostdefi-eligibility.yml
source_heading: Eligibility
source_page: https://hostdefi.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HostDeFi\naid: hostdefi\nurl: https://hostdefi.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access from comprehensively sanctioned jurisdictions is prohibited where prohibited by applicable law.\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned jurisdictions\n  text: Access from comprehensively sanctioned jurisdictions is prohibited where prohibited by applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hostdefi/eligibility/hostdefi-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from HostDeFi's own page on 2026-11-09.
synthetic: false
tags:
- Solana
- Token Risk
- DeFi
- rug-pull
- x402
- A2A
---
