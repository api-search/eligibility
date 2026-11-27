---
api_specs:
- filename: tesseract-clients-api-openapi.yml
  format: yaml
  label: Tesseract Clients API
  slug: tesseract-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesseract/openapi/tesseract-clients-api-openapi.yml
- filename: tesseract-health-api-openapi.yml
  format: yaml
  label: Tesseract Health API
  slug: tesseract-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesseract/openapi/tesseract-health-api-openapi.yml
- filename: tesseract-insights-api-openapi.yml
  format: yaml
  label: Tesseract Insights API
  slug: tesseract-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesseract/openapi/tesseract-insights-api-openapi.yml
- filename: tesseract-strategies-api-openapi.yml
  format: yaml
  label: Tesseract Strategies API
  slug: tesseract-strategies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesseract/openapi/tesseract-strategies-api-openapi.yml
- filename: tesseract-vaults-api-openapi.yml
  format: yaml
  label: Tesseract Vaults API
  slug: tesseract-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesseract/openapi/tesseract-vaults-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - EU
    text: these websites and services are primarily intended for individuals residing in the EU countries, unless otherwise specified. The materials on these websites are not intended for individuals residing in jurisdictions where such activities are not authorized by the relevant local laws.
  entity_types:
  - text: these websites and services are primarily intended for individuals residing in the EU countries
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Tesseract
provenance_date: '2026-11-10'
provider_name: Tesseract
provider_slug: tesseract
slug: tesseract-eligibility
source_date: '2026-11-10'
source_filename: tesseract-eligibility.yml
source_heading: Eligibility
source_page: https://tesseract.fi/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tesseract\naid: tesseract\nurl: https://tesseract.fi/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - EU\n  excluded: []\n  text: these websites and services are primarily intended for individuals residing in the EU countries, unless\n    otherwise specified. The materials on these websites are not intended for individuals residing in jurisdictions\n    where such activities are not authorized by the relevant local laws.\nentity_types:\n- type: individual\n  text: these websites and services are primarily intended for individuals residing in the EU countries\nrestricted_uses: []\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tesseract/eligibility/tesseract-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Tesseract's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Cryptocurrency
- DeFi
- Lending
- Yield
- Digital Assets
- Ethereum
- MiCA
- Vault
- Institutional
---
