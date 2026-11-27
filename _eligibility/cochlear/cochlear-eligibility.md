---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Age-restricted areas
    text: You may not use age-restricted areas of our Websites if you do not meet the applicable age requirements.
  - summary: Off-label product promotion
    text: promotes an off-label use, or a use not approved by the relevant regulatory body in your country, of any product manufactured or distributed by the Cochlear Group.
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
name: Cochlear
provenance_date: '2026-11-09'
provider_name: Cochlear
provider_slug: cochlear
slug: cochlear-eligibility
source_date: '2026-11-09'
source_filename: cochlear-eligibility.yml
source_heading: Eligibility
source_page: https://www.cochlear.com/us/en/corporate/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cochlear\naid: cochlear\nurl: https://www.cochlear.com/us/en/corporate/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Age-restricted areas\n  text: You may not use age-restricted areas of our Websites if you do not meet the applicable age requirements.\n- summary: Off-label product promotion\n  text: promotes an off-label use, or a use not approved by the relevant regulatory body in your country, of any\n    product manufactured or distributed by the Cochlear Group.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cochlear/eligibility/cochlear-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Cochlear's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hearing
- Medical Devices
- Healthcare
- Implantable Technology
---
