---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for businesses.
    type: business
  minimum_age:
    text: you represent that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Political campaigning and regulated industries
    text: use the Services for political campaigning, regulated industries, or other use cases prohibited by applicable platform or carrier rules without our prior written consent
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
name: Chert
provenance_date: '2026-11-09'
provider_name: Chert
provider_slug: chert
slug: chert-eligibility
source_date: '2026-11-09'
source_filename: chert-eligibility.yml
source_heading: Eligibility
source_page: https://www.trychert.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chert\naid: chert\nurl: https://www.trychert.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended for businesses.\nrestricted_uses:\n- summary: Political campaigning and regulated industries\n  text: use the Services for political campaigning, regulated industries, or other use cases prohibited by applicable\n    platform or carrier rules without our prior written consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent\
  \ that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/chert/eligibility/chert-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Chert's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Messaging
- iMessage
- Communications
- Webhook
- CRM Integration
---
