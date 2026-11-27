---
api_specs:
- filename: mavenir-onetoonecall-api-openapi.yml
  format: yaml
  label: Mavenir One To One Call API
  slug: mavenir-onetoonecall-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mavenir/openapi/mavenir-onetoonecall-api-openapi.yml
- filename: mavenir-push-token-api-openapi.yml
  format: yaml
  label: Mavenir Push Token API
  slug: mavenir-push-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mavenir/openapi/mavenir-push-token-api-openapi.yml
- filename: mavenir-racm-api-openapi.yml
  format: yaml
  label: Mavenir RACM API
  slug: mavenir-racm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mavenir/openapi/mavenir-racm-api-openapi.yml
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
  - summary: Informational, non-commercial use only
    text: This Site is made available to you solely for informational, non-commercial use
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
name: Mavenir
provenance_date: '2026-11-10'
provider_name: Mavenir
provider_slug: mavenir
slug: mavenir-eligibility
source_date: '2026-11-10'
source_filename: mavenir-eligibility.yml
source_heading: Eligibility
source_page: https://www.mavenir.com/terms-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mavenir\naid: mavenir\nurl: https://www.mavenir.com/terms-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Informational, non-commercial use only\n  text: This Site is made available to you solely for informational, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mavenir/eligibility/mavenir-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Mavenir's own page on 2026-11-10.
synthetic: false
tags:
- Telecommunications
- United States
- Network Vendor
- Network APIs
- CAMARA
- Open Gateway
- BSS
- OSS
- TM Forum
- Open RAN
- 5G
- IMS
- Messaging
- Network Exposure Function
- Standards
---
