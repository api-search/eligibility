---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may only access and use the Services if you are at least the age of majority in your state or province of residence (which is usually 18 years or age or older)
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal non-commercial use only
    text: The Services and the Content are intended solely for personal and non-commercial use by you.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may verify certain items before the order is fulfilled, including without limitation your personal information, your payment information and your creditworthiness
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Colorescience
provenance_date: '2026-11-09'
provider_name: Colorescience
provider_slug: colorescience
slug: colorescience-eligibility
source_date: '2026-11-09'
source_filename: colorescience-eligibility.yml
source_heading: Eligibility
source_page: https://www.colorescience.com/pages/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Colorescience\naid: colorescience\nurl: https://www.colorescience.com/pages/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may only access and use the Services if you are at least the age of majority in your state or province\n    of residence (which is usually 18 years or age or older)\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: The Services and the Content are intended solely for personal and non-commercial use by you.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: we may verify certain items before the order is fulfilled, including without limitation your personal information,\n    your payment information and your creditworthiness\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/colorescience/eligibility/colorescience-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Colorescience's own page on 2026-11-09.
synthetic: false
tags:
- Skincare
- Sunscreen
- Cosmetics
- Health
- E-Commerce
---
