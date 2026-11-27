---
api_specs:
- filename: tealium-auth-api-openapi.yml
  format: yaml
  label: Tealium Auth API
  slug: tealium-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tealium/openapi/tealium-auth-api-openapi.yml
- filename: tealium-collect-api-openapi.yml
  format: yaml
  label: Tealium Collect API
  slug: tealium-collect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tealium/openapi/tealium-collect-api-openapi.yml
- filename: tealium-customer-api-openapi.yml
  format: yaml
  label: Tealium Customer API
  slug: tealium-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tealium/openapi/tealium-customer-api-openapi.yml
- filename: tealium-personalization-api-openapi.yml
  format: yaml
  label: Tealium Personalization API
  slug: tealium-personalization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tealium/openapi/tealium-personalization-api-openapi.yml
- filename: tealium-privacy-api-openapi.yml
  format: yaml
  label: Tealium Privacy API
  slug: tealium-privacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tealium/openapi/tealium-privacy-api-openapi.yml
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
  - summary: Unlawful or objectionable content
    text: 'You agree not to use the Website to collect, upload, transmit, display, or distribute any Content that: violates any third-party right'
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
name: Tealium
provenance_date: '2026-11-10'
provider_name: Tealium
provider_slug: tealium
slug: tealium-eligibility
source_date: '2026-11-10'
source_filename: tealium-eligibility.yml
source_heading: Eligibility
source_page: https://tealium.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tealium\naid: tealium\nurl: https://tealium.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or objectionable content\n  text: 'You agree not to use the Website to collect, upload, transmit, display, or distribute any Content that:\n    violates any third-party right'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tealium/eligibility/tealium-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Tealium's own page on 2026-11-10.
synthetic: false
tags:
- Customer Data Platform
- CDP
- Tag Management
- AudienceStream
- Real-Time Events
- Visitor Profiles
- Audience Segmentation
- Data Collection
- Privacy Compliance
- Personalization
---
