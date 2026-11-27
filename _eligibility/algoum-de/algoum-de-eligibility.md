---
api_specs:
- filename: algoum-de-common-api-openapi.yml
  format: yaml
  label: algoum-de Common API
  slug: algoum-de-common-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algoum-de/openapi/algoum-de-common-api-openapi.yml
- filename: algoum-de-events-api-openapi.yml
  format: yaml
  label: algoum-de Events API
  slug: algoum-de-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algoum-de/openapi/algoum-de-events-api-openapi.yml
- filename: algoum-de-insider-api-openapi.yml
  format: yaml
  label: algoum-de Insider API
  slug: algoum-de-insider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algoum-de/openapi/algoum-de-insider-api-openapi.yml
- filename: algoum-de-institutional-api-openapi.yml
  format: yaml
  label: algoum-de Institutional API
  slug: algoum-de-institutional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algoum-de/openapi/algoum-de-institutional-api-openapi.yml
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
  - summary: Personal use only API key
    text: The API key is intended strictly for personal use and must not be passed on to third parties.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration is required for access to certain features.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: algoum-de
provenance_date: '2026-11-09'
provider_name: Algoum
provider_slug: algoum-de
slug: algoum-de-eligibility
source_date: '2026-11-09'
source_filename: algoum-de-eligibility.yml
source_heading: Eligibility
source_page: https://algoum.de/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: algoum-de\naid: algoum-de\nurl: https://algoum.de/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal use only API key\n  text: The API key is intended strictly for personal use and must not be passed on to third parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registration is required for access to certain features.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/algoum-de/eligibility/algoum-de-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from algoum-de's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- SEC
- Insider Trading
---
