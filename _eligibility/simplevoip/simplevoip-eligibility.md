---
api_specs:
- filename: simplevoip-call-recordings-api-openapi.yml
  format: yaml
  label: SimpleVoIP Call Recordings API
  slug: simplevoip-call-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplevoip/openapi/simplevoip-call-recordings-api-openapi.yml
- filename: simplevoip-cdr-api-openapi.yml
  format: yaml
  label: SimpleVoIP CDR API
  slug: simplevoip-cdr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplevoip/openapi/simplevoip-cdr-api-openapi.yml
- filename: simplevoip-music-on-hold-api-openapi.yml
  format: yaml
  label: SimpleVoIP Music on Hold API
  slug: simplevoip-music-on-hold-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplevoip/openapi/simplevoip-music-on-hold-api-openapi.yml
- filename: simplevoip-sms-api-openapi.yml
  format: yaml
  label: SimpleVoIP SMS API
  slug: simplevoip-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplevoip/openapi/simplevoip-sms-api-openapi.yml
- filename: simplevoip-time-of-day-api-openapi.yml
  format: yaml
  label: SimpleVoIP Time of Day API
  slug: simplevoip-time-of-day-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplevoip/openapi/simplevoip-time-of-day-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: SimpleVoIP provides services and equipment intended solely for business use
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal use only
    text: Customer agrees and represents that it is purchasing the Service for its own internal use.
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
name: SimpleVoIP
provenance_date: '2026-11-10'
provider_name: SimpleVoIP
provider_slug: simplevoip
slug: simplevoip-eligibility
source_date: '2026-11-10'
source_filename: simplevoip-eligibility.yml
source_heading: Eligibility
source_page: https://support.simplevoip.com/hc/en-us/articles/360056923954-SimpleVoIP-Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SimpleVoIP\naid: simplevoip\nurl: https://support.simplevoip.com/hc/en-us/articles/360056923954-SimpleVoIP-Terms-of-Service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: SimpleVoIP provides services and equipment intended solely for business use\nrestricted_uses:\n- summary: Internal use only\n  text: Customer agrees and represents that it is purchasing the Service for its own internal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/simplevoip/eligibility/simplevoip-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from SimpleVoIP's own page on 2026-11-10.
synthetic: false
tags:
- VoIP
- Communications
- UCaaS
- Artificial Intelligence
- Small Business
---
