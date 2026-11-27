---
api_specs:
- filename: kaiko-canton-oracle-api-openapi.yml
  format: yaml
  label: Kaiko Canton Oracle API
  slug: kaiko-canton-oracle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiko/openapi/kaiko-canton-oracle-api-openapi.yml
- filename: kaiko-index-reference-data-api-openapi.yml
  format: yaml
  label: Kaiko Index Reference Data API
  slug: kaiko-index-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiko/openapi/kaiko-index-reference-data-api-openapi.yml
- filename: kaiko-indices-api-openapi.yml
  format: yaml
  label: Kaiko Indices API
  slug: kaiko-indices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiko/openapi/kaiko-indices-api-openapi.yml
- filename: kaiko-supply-api-openapi.yml
  format: yaml
  label: Kaiko Supply API
  slug: kaiko-supply-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiko/openapi/kaiko-supply-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The licence is described as a non-exclusive, non-transferable, worldwide, limited license.
  entity_types:
  - text: use solely in connection with Client’s internal business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No redistribution substituting for data access
    text: Client shall be prohibited from providing or redistributing the Data to any third party, including customers, to the extent such redistribution could reasonably be expected to be a substitute for access or a license to Data.
  - summary: Commercialisation requires consent
    text: To the extent, Client seeks to commercialize any derived works into a client-facing product, Client shall contact Supplier to seek consent and execute additional terms and conditions.
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
name: Kaiko
provenance_date: '2026-11-09'
provider_name: Kaiko
provider_slug: kaiko
slug: kaiko-eligibility
source_date: '2026-11-09'
source_filename: kaiko-eligibility.yml
source_heading: Eligibility
source_page: https://www.kaiko.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kaiko\naid: kaiko\nurl: https://www.kaiko.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The licence is described as a non-exclusive, non-transferable, worldwide, limited license.\nentity_types:\n- type: business\n  text: use solely in connection with Client’s internal business purposes\nrestricted_uses:\n- summary: No redistribution substituting for data access\n  text: Client shall be prohibited from providing or redistributing the Data to any third party, including customers,\n    to the extent such redistribution could reasonably be expected to be a substitute for\
  \ access or a license to\n    Data.\n- summary: Commercialisation requires consent\n  text: To the extent, Client seeks to commercialize any derived works into a client-facing product, Client shall\n    contact Supplier to seek consent and execute additional terms and conditions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kaiko/eligibility/kaiko-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Kaiko's own page on 2026-11-09.
synthetic: false
tags:
- Web3
- Cryptocurrency
- Market Data
- Institutional
- Foreign Exchange
- Indices
- Onchain
- Streaming
---
