---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use or access our Services, you must be at least 18 years old.
    type: individual
  minimum_age:
    text: To use or access our Services, you must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: We only supply the Services for domestic and private use.
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
name: Ray
provenance_date: '2026-11-10'
provider_name: Ray
provider_slug: rayfit-com
slug: rayfit-com-eligibility
source_date: '2026-11-10'
source_filename: rayfit-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.rayfit.com/terms-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ray\naid: rayfit-com\nurl: https://www.rayfit.com/terms-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use or access our Services, you must be at least 18 years old.\nrestricted_uses:\n- summary: Personal use only\n  text: We only supply the Services for domestic and private use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use or access our Services, you must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/rayfit-com/eligibility/rayfit-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ray's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Fitness
- Health
- Personal Trainer
- Wellness
- Company
---
