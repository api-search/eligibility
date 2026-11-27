---
api_specs:
- filename: workwae-com-v1-openapi.json
  format: json
  label: Workwae API V1 API
  slug: workwae-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workwae-com/openapi/_original/workwae-com-v1-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to form a binding contract to create a workspace.
    type: individual
  - text: If you use the Service for an organization, you accept these Terms on its behalf and confirm you are authorized to do so
    type: business
  minimum_age:
    text: You must be at least 18 and able to form a binding contract to create a workspace.
    value: '18'
  restricted_uses:
  - summary: Spam and phishing
    text: send spam, unsolicited bulk mail, phishing or messages with forged headers
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
name: workwae-com
provenance_date: '2026-11-10'
provider_name: workwae-com
provider_slug: workwae-com
slug: workwae-com-eligibility
source_date: '2026-11-10'
source_filename: workwae-com-eligibility.yml
source_heading: Eligibility
source_page: https://workwae.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: workwae-com\naid: workwae-com\nurl: https://workwae.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to form a binding contract to create a workspace.\n- type: business\n  text: If you use the Service for an organization, you accept these Terms on its behalf and confirm you are authorized\n    to do so\nrestricted_uses:\n- summary: Spam and phishing\n  text: send spam, unsolicited bulk mail, phishing or messages with forged headers\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a binding contract to create a workspace.\n"
source_yaml_url: https://artifacts.apis.io/workwae-com/eligibility/workwae-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from workwae-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email
- Calendar
- Contacts
- Scheduling
- Artificial Intelligence
---
