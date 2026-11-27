---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using our services, you confirm that you have the right to post vacancies and other advertisements on behalf of your organization
    type: business
  minimum_age:
    text: Our Website is not directed towards children under the age of 15.
    value: '15'
  restricted_uses:
  - summary: Uses not expressly granted
    text: Any use of the Website not expressly granted herein is prohibited.
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
name: Wuzzuf
provenance_date: '2026-11-10'
provider_name: Wuzzuf
provider_slug: wuzzuf
slug: wuzzuf-eligibility
source_date: '2026-11-10'
source_filename: wuzzuf-eligibility.yml
source_heading: Eligibility
source_page: https://wuzzuf.net/policies
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wuzzuf\naid: wuzzuf\nurl: https://wuzzuf.net/policies\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By using our services, you confirm that you have the right to post vacancies and other advertisements on\n    behalf of your organization\nrestricted_uses:\n- summary: Uses not expressly granted\n  text: Any use of the Website not expressly granted herein is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '15'\n  text: Our Website is not directed towards children under\
  \ the age of 15.\n"
source_yaml_url: https://artifacts.apis.io/wuzzuf/eligibility/wuzzuf-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Wuzzuf's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Job
- Recruiting
- Careers
- Employment
- Human Resources
- Egypt
---
