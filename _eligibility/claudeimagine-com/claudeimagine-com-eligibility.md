---
api_specs:
- filename: claudeimagine-com-openapi-generated.yml
  format: yaml
  label: Claude Imagine API
  slug: claudeimagine-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claudeimagine-com/openapi/_ae-authored/claudeimagine-com-openapi-generated.yml
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
  - summary: Illegal or unauthorized use
    text: Using the service for any illegal or unauthorized purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access certain features of the service, you need to create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Claude Imagine
provenance_date: '2026-11-09'
provider_name: Claude Imagine
provider_slug: claudeimagine-com
slug: claudeimagine-com-eligibility
source_date: '2026-11-09'
source_filename: claudeimagine-com-eligibility.yml
source_heading: Eligibility
source_page: https://claudeimagine.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Claude Imagine\naid: claudeimagine-com\nurl: https://claudeimagine.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: Using the service for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access certain features of the service, you need to create an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/claudeimagine-com/eligibility/claudeimagine-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Claude Imagine's own page on 2026-11-09.
synthetic: false
tags:
- AI Image Generation
- Video Generation
- Credit Pricing
---
