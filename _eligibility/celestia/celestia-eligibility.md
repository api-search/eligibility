---
api_specs:
- filename: celestia-blob-api-openapi.yml
  format: yaml
  label: Celestia Node Blob API
  slug: celestia-blob-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celestia/openapi/celestia-blob-api-openapi.yml
- filename: celestia-contact-api-openapi.yml
  format: yaml
  label: Celestia Contact API
  slug: celestia-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celestia/openapi/celestia-contact-api-openapi.yml
- filename: celestia-health-api-openapi.yml
  format: yaml
  label: Celestia Health API
  slug: celestia-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celestia/openapi/celestia-health-api-openapi.yml
- filename: celestia-subscribe-api-openapi.yml
  format: yaml
  label: Celestia Subscribe API
  slug: celestia-subscribe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celestia/openapi/celestia-subscribe-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: located or organized in any U.S. embargoed countries or any country that has been designated by the U.S. Government as a “terrorist supporting” country (currently, the Crimea region of Ukraine, Cuba, Iran, North Korea, Syria
  entity_types:
  - text: In order to use the Services, you must be thirteen 13 years of age or older
    type: individual
  - text: If you use the Services on behalf of a company or other entity then
    type: business
  minimum_age:
    text: you must be thirteen 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: Illegal activity
    text: will not be using the Services for any illegal activity
  - summary: Sanctioned parties
    text: listed on any U.S., EU (including its Member States) or UK list of prohibited or restricted parties
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Celestia
provenance_date: '2026-11-09'
provider_name: Celestia
provider_slug: celestia
slug: celestia-eligibility
source_date: '2026-11-09'
source_filename: celestia-eligibility.yml
source_heading: Eligibility
source_page: https://celestia.org/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Celestia\naid: celestia\nurl: https://celestia.org/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: located or organized in any U.S. embargoed countries or any country that has been designated by the U.S.\n    Government as a “terrorist supporting” country (currently, the Crimea region of Ukraine, Cuba, Iran, North Korea,\n    Syria\nentity_types:\n- type: individual\n  text: In order to use the Services, you must be thirteen 13 years of age or older\n- type: business\n  text: If you use the Services on behalf of a company or other entity then\nrestricted_uses:\n\
  - summary: Illegal activity\n  text: will not be using the Services for any illegal activity\n- summary: Sanctioned parties\n  text: listed on any U.S., EU (including its Member States) or UK list of prohibited or restricted parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you must be thirteen 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/celestia/eligibility/celestia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Celestia's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Data Availability
- Web3
- Infrastructure
- Open Source
- JSON-RPC
- Modular Blockchain
- Rollup
- Cryptography
- Developer Tools
---
