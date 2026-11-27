---
api_specs:
- filename: callrail-accounts-api-openapi.yml
  format: yaml
  label: CallRail Accounts API
  slug: callrail-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callrail/openapi/callrail-accounts-api-openapi.yml
- filename: callrail-calls-api-openapi.yml
  format: yaml
  label: CallRail Calls API
  slug: callrail-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callrail/openapi/callrail-calls-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You accept that the Services are provided for professional use only
    type: business
  minimum_age:
    text: The Services are intended for use only by users that are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Not for protected health information
    text: You acknowledge that certain Services are not suitable for the provision, transmission, receipt, or other processing of protected health information
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
name: CallRail
provenance_date: '2026-11-09'
provider_name: CallRail
provider_slug: callrail
slug: callrail-eligibility
source_date: '2026-11-09'
source_filename: callrail-eligibility.yml
source_heading: Eligibility
source_page: https://www.callrail.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CallRail\naid: callrail\nurl: https://www.callrail.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You accept that the Services are provided for professional use only\nrestricted_uses:\n- summary: Not for protected health information\n  text: You acknowledge that certain Services are not suitable for the provision, transmission, receipt, or other\n    processing of protected health information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: The Services are intended for use only by users that are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/callrail/eligibility/callrail-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CallRail's own page on 2026-11-09.
synthetic: false
tags:
- Call Tracking
- Conversation Intelligence
- Marketing Attribution
- Lead Tracking
- Telephony
- Analytics
- Form Tracking
- Attribution
---
