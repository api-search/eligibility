---
api_specs:
- filename: askedthrice-com-embeds-api-openapi.yml
  format: yaml
  label: Asked Thrice Embeds API
  slug: askedthrice-com-embeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askedthrice-com/openapi/askedthrice-com-embeds-api-openapi.yml
- filename: askedthrice-com-scans-api-openapi.yml
  format: yaml
  label: Asked Thrice Scans API
  slug: askedthrice-com-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askedthrice-com/openapi/askedthrice-com-scans-api-openapi.yml
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
  - summary: Reselling or running as a service for others
    text: does not let you resell scans or run the product as a service for other people
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a code sent to your email, so keep access to that inbox.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Asked Thrice
provenance_date: '2026-11-09'
provider_name: Asked Thrice
provider_slug: askedthrice-com
slug: askedthrice-com-eligibility
source_date: '2026-11-09'
source_filename: askedthrice-com-eligibility.yml
source_heading: Eligibility
source_page: https://askedthrice.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Asked Thrice\naid: askedthrice-com\nurl: https://askedthrice.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Reselling or running as a service for others\n  text: does not let you resell scans or run the product as a service for other people\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with a code sent to your email, so keep access to that inbox.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/askedthrice-com/eligibility/askedthrice-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Asked Thrice's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Visibility
- Audit
- Generative AI
- Brand Analytics
---
