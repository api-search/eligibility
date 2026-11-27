---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The Service is intended for users located within the United States and Canada. We make no representation that the Service is appropriate or available for use outside of the United States and Canada.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use by insurance carriers/agents using the Service to serve end users
    text: If you are an insurance carrier, insurance agent, broker, third party claims administrator or employee of the foregoing using the Service to provide services to end users, please note your use of the Service (including the app) is subject to the separate commercial agreement
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
name: Hi Marley
provenance_date: '2026-11-09'
provider_name: Hi Marley
provider_slug: hi-marley
slug: hi-marley-eligibility
source_date: '2026-11-09'
source_filename: hi-marley-eligibility.yml
source_heading: Eligibility
source_page: https://www.himarley.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hi Marley\naid: hi-marley\nurl: https://www.himarley.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The Service is intended for users located within the United States and Canada. We make no representation\n    that the Service is appropriate or available for use outside of the United States and Canada.\nentity_types: []\nrestricted_uses:\n- summary: Commercial use by insurance carriers/agents using the Service to serve end users\n  text: If you are an insurance carrier, insurance agent, broker, third party claims administrator or employee of\n    the\
  \ foregoing using the Service to provide services to end users, please note your use of the Service (including\n    the app) is subject to the separate commercial agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hi-marley/eligibility/hi-marley-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Hi Marley's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance Tech
- Insurance
- Claims
- Messaging
- SMS
- Conversational AI
- Property and Casualty
- Customer Communication
- FNOL
---
