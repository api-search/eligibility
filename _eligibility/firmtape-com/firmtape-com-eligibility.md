---
api_specs:
- filename: firmtape-com-levels-api-openapi.yml
  format: yaml
  label: firmtape-com Levels API
  slug: firmtape-com-levels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firmtape-com/openapi/firmtape-com-levels-api-openapi.yml
- filename: firmtape-com-days-api-openapi.yml
  format: yaml
  label: FirmTape Days API
  slug: firmtape-com-days-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firmtape-com/openapi/firmtape-com-days-api-openapi.yml
- filename: firmtape-com-session-api-openapi.yml
  format: yaml
  label: FirmTape Session API
  slug: firmtape-com-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firmtape-com/openapi/firmtape-com-session-api-openapi.yml
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
  - summary: No investment advice reliance
    text: Do not use FirmTape as the sole basis for a trade.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Accounts exist only to hold a subscription and are created when you subscribe.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FirmTape
provenance_date: '2026-11-09'
provider_name: FirmTape
provider_slug: firmtape-com
slug: firmtape-com-eligibility
source_date: '2026-11-09'
source_filename: firmtape-com-eligibility.yml
source_heading: Eligibility
source_page: https://firmtape.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FirmTape\naid: firmtape-com\nurl: https://firmtape.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No investment advice reliance\n  text: Do not use FirmTape as the sole basis for a trade.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accounts exist only to hold a subscription and are created when you subscribe.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/firmtape-com/eligibility/firmtape-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from FirmTape's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Data
- Analytics
- Options
- Gamma
---
