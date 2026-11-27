---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to register and use the Services, or You must be the parent or legal guardian for someone under age 18 who is enrolled in the Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to register and use the Services, or You must be the parent or legal guardian for someone under age 18 who is enrolled in the Services.
    value: '18'
  restricted_uses:
  - summary: Website not for children under 13
    text: The Website is not directed to or intended for children under the age of 13 and we do not knowingly collect personal information from such children without parental consent.
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
name: Sprinter Health
provenance_date: '2026-11-10'
provider_name: Sprinter Health
provider_slug: sprinter-health
slug: sprinter-health-eligibility
source_date: '2026-11-10'
source_filename: sprinter-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.sprinterhealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sprinter Health\naid: sprinter-health\nurl: https://www.sprinterhealth.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to register and use the Services, or You must be the parent or legal guardian\n    for someone under age 18 who is enrolled in the Services.\nrestricted_uses:\n- summary: Website not for children under 13\n  text: The Website is not directed to or intended for children under the age of 13 and we do not knowingly collect\n    personal information from such children\
  \ without parental consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register and use the Services, or You must be the parent or legal guardian\n    for someone under age 18 who is enrolled in the Services.\n"
source_yaml_url: https://artifacts.apis.io/sprinter-health/eligibility/sprinter-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sprinter Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- In-Home Care
- Preventive Care
- Diagnostics
- Telehealth
- Care Navigation
---
