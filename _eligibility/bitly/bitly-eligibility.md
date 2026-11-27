---
api_specs:
- filename: bitly-bsds-api-openapi.yml
  format: yaml
  label: Bitly BSDs API
  slug: bitly-bsds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-bsds-api-openapi.yml
- filename: bitly-bitlinks-api-openapi.yml
  format: yaml
  label: Bitly Bitlinks API
  slug: bitly-bitlinks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-bitlinks-api-openapi.yml
- filename: bitly-campaigns-api-openapi.yml
  format: yaml
  label: Bitly Campaigns API
  slug: bitly-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-campaigns-api-openapi.yml
- filename: bitly-custom-bitlinks-api-openapi.yml
  format: yaml
  label: Bitly Custom Bitlinks API
  slug: bitly-custom-bitlinks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-custom-bitlinks-api-openapi.yml
- filename: bitly-groups-api-openapi.yml
  format: yaml
  label: Bitly Groups API
  slug: bitly-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-groups-api-openapi.yml
- filename: bitly-organizations-api-openapi.yml
  format: yaml
  label: Bitly Organizations API
  slug: bitly-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-organizations-api-openapi.yml
- filename: bitly-qr-codes-api-openapi.yml
  format: yaml
  label: Bitly QR Codes API
  slug: bitly-qr-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-qr-codes-api-openapi.yml
- filename: bitly-user-api-openapi.yml
  format: yaml
  label: Bitly User API
  slug: bitly-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-user-api-openapi.yml
- filename: bitly-webhooks-api-openapi.yml
  format: yaml
  label: Bitly Webhooks API
  slug: bitly-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-webhooks-api-openapi.yml
- filename: bitly-apps-api-openapi.yml
  format: yaml
  label: Bitly Apps API
  slug: bitly-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-apps-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: does NOT contain any personally identifiable information or persistent identifiers from individuals under the age of 16.
    value: '16'
  restricted_uses:
  - summary: Competitors barred
    text: you agree that you will not access the Bitly Services for competitive purposes or if you are a competitor of Bitly.
  - summary: Life-critical uses barred
    text: any activities where the use or failure of the Bitly Services could lead to death, personal injury or property or environmental damage
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
name: Bitly
provenance_date: '2026-11-09'
provider_name: Bitly
provider_slug: bitly
slug: bitly-eligibility
source_date: '2026-11-09'
source_filename: bitly-eligibility.yml
source_heading: Eligibility
source_page: https://bitly.com/pages/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bitly\naid: bitly\nurl: https://bitly.com/pages/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Competitors barred\n  text: you agree that you will not access the Bitly Services for competitive purposes or if you are a competitor\n    of Bitly.\n- summary: Life-critical uses barred\n  text: any activities where the use or failure of the Bitly Services could lead to death, personal injury or property\n    or environmental damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '16'\n  text: does NOT contain any personally identifiable information or persistent identifiers from individuals under\n    the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/bitly/eligibility/bitly-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bitly's own page on 2026-11-09.
synthetic: false
tags:
- Links
- URL Shorteners
- QR Codes
- Analytics
- Marketing
- Link Management
- Webhook
- Attribution
- Agents
- MCP
---
