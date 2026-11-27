---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Owner of the Service is based in the United States, and we make no claims that the Service or any of its content is accessible or appropriate outside of the United States.
  entity_types:
  - text: You must be over the age of 18 to sign up for an account to use our Service.
    type: individual
  minimum_age:
    text: You must be over the age of 18 to sign up for an account to use our Service.
    value: '18'
  restricted_uses:
  - summary: Commercial use of the Service
    text: (1) access or use for any commercial purposes any part of the Service or any services or materials available through the Service
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
name: Volley
provenance_date: '2026-11-10'
provider_name: Volley
provider_slug: volley
slug: volley-eligibility
source_date: '2026-11-10'
source_filename: volley-eligibility.yml
source_heading: Eligibility
source_page: https://www.weekend.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Volley\naid: volley\nurl: https://www.weekend.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Owner of the Service is based in the United States, and we make no claims that the Service or any of\n    its content is accessible or appropriate outside of the United States.\nentity_types:\n- type: individual\n  text: You must be over the age of 18 to sign up for an account to use our Service.\nrestricted_uses:\n- summary: Commercial use of the Service\n  text: (1) access or use for any commercial purposes any part of the Service or any services or materials available\n\
  \    through the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be over the age of 18 to sign up for an account to use our Service.\n"
source_yaml_url: https://artifacts.apis.io/volley/eligibility/volley-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Volley's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Voice
- Games
- Entertainment
- Smart Speaker
- Connected TV
- Artificial Intelligence
- Consumer
---
