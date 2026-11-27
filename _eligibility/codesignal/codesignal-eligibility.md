---
api_specs:
- filename: codesignal-organization-api-openapi.yml
  format: yaml
  label: Codesignal Organization API
  slug: codesignal-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codesignal/openapi/codesignal-organization-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you warrant that you ... are not located in, or a resident of, any country that is subject to applicable U.S. trade sanctions or embargoes (such as Cuba, Iran, North Korea, Sudan, Syria, or the Crimea, Donetsk, or Luhansk regions).
  entity_types:
  - text: If your organization or entity is a Customer of CodeSignal then your use of the Services is also governed by the terms of either the CodeSignal Master Services Agreement or a separate executed agreement
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 13 years of age
    value: '13'
  restricted_uses:
  - summary: Use must comply with law and not be for third parties
    text: You will only use the Services for your own internal, personal, non-commercial use, and not on behalf of or for the benefit of any third party
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
name: Codesignal
provenance_date: '2026-11-09'
provider_name: Codesignal
provider_slug: codesignal
slug: codesignal-eligibility
source_date: '2026-11-09'
source_filename: codesignal-eligibility.yml
source_heading: Eligibility
source_page: https://codesignal.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Codesignal\naid: codesignal\nurl: https://codesignal.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you warrant that you ... are not located in, or a resident of, any country that is subject to applicable\n    U.S. trade sanctions or embargoes (such as Cuba, Iran, North Korea, Sudan, Syria, or the Crimea, Donetsk, or\n    Luhansk regions).\nentity_types:\n- type: business\n  text: If your organization or entity is a Customer of CodeSignal then your use of the Services is also governed\n    by the terms of either the CodeSignal Master Services Agreement or a separate executed\
  \ agreement\nrestricted_uses:\n- summary: Use must comply with law and not be for third parties\n  text: You will only use the Services for your own internal, personal, non-commercial use, and not on behalf of\n    or for the benefit of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 13 years\n    of age\n"
source_yaml_url: https://artifacts.apis.io/codesignal/eligibility/codesignal-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Codesignal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Technical Interview
- Skills Assessment
- Hiring
- Recruiting
- Developer Skills
- Assessment
- Education
- GraphQL
- Webhook
---
