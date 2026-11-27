---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: business entities, including sole proprietorship firms, companies and partnerships
    type: business
  minimum_age:
    text: if it is discovered that the Member is under the age of 18 (eighteen) years
    value: '18'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: 'You shall not host, display, upload, modify, publish, transmit, update or share any information that:'
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
name: Airblack
provenance_date: '2026-11-09'
provider_name: Airblack
provider_slug: airblack
slug: airblack-eligibility
source_date: '2026-11-09'
source_filename: airblack-eligibility.yml
source_heading: Eligibility
source_page: https://www.airblack.com/terms/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airblack\naid: airblack\nurl: https://www.airblack.com/terms/termsofservice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: business entities, including sole proprietorship firms, companies and partnerships\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: 'You shall not host, display, upload, modify, publish, transmit, update or share any information that:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if it is discovered that the Member is\
  \ under the age of 18 (eighteen) years\n"
source_yaml_url: https://artifacts.apis.io/airblack/eligibility/airblack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Airblack's own page on 2026-11-09.
synthetic: false
tags:
- Education
- EdTech
- E-Learning
- Skilling
- Beauty
- Makeup
- Culinary
- Creator Economy
- India
- Company
---
