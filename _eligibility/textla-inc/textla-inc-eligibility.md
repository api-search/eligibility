---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the Site may only be used for sending and receiving communications with individuals who are located within the United States.
  entity_types:
  - text: whether personally or on behalf of an entity (“you” or “your”)
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Recipients limited to United States
    text: the Site may only be used for sending and receiving communications with individuals who are located within the United States.
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
name: Textla
provenance_date: '2026-11-10'
provider_name: Textla
provider_slug: textla-inc
slug: textla-inc-eligibility
source_date: '2026-11-10'
source_filename: textla-inc-eligibility.yml
source_heading: Eligibility
source_page: https://www.textla.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Textla\naid: textla-inc\nurl: https://www.textla.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the Site may only be used for sending and receiving communications with individuals who are located within\n    the United States.\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity (“you” or “your”)\nrestricted_uses:\n- summary: Recipients limited to United States\n  text: the Site may only be used for sending and receiving communications with individuals who are located within\n    the United States.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/textla-inc/eligibility/textla-inc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Textla's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SMS
- Text Messaging
- Business Messaging
- Bulk SMS
- Communications
- Marketing
- Customer Engagement
---
