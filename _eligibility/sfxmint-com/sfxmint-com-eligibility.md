---
api_specs:
- filename: sfxmint-com-generation-api-openapi.yml
  format: yaml
  label: SFXMint Generation API
  slug: sfxmint-com-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sfxmint-com/openapi/sfxmint-com-generation-api-openapi.yml
- filename: sfxmint-com-library-api-openapi.yml
  format: yaml
  label: SFXMint Library API
  slug: sfxmint-com-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sfxmint-com/openapi/sfxmint-com-library-api-openapi.yml
claim_count: 1
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
  - summary: Acceptable use
    text: Do not use SFXMint to break the law or anyone's rights, to get around usage limits or payment, to resell access to the API or generation, or to overload the service.
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
name: SFXMint
provenance_date: '2026-11-10'
provider_name: SFXMint
provider_slug: sfxmint-com
slug: sfxmint-com-eligibility
source_date: '2026-11-10'
source_filename: sfxmint-com-eligibility.yml
source_heading: Eligibility
source_page: https://sfxmint.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SFXMint\naid: sfxmint-com\nurl: https://sfxmint.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use\n  text: Do not use SFXMint to break the law or anyone's rights, to get around usage limits or payment, to resell\n    access to the API or generation, or to overload the service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sfxmint-com/eligibility/sfxmint-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from SFXMint's own page on 2026-11-10.
synthetic: false
tags:
- Sound Effects
- CC0
- AI Studio
- Games
- Free
---
