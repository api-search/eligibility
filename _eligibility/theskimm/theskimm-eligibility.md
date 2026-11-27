---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Everyday Health makes no representation or warranty that the content and materials on the Sites or the Services are appropriate or available for use in locations outside the United States.
  entity_types:
  - text: Services are for your personal and non-commercial use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial informational use only
    text: The Sites and Services offer health, fitness and nutrition related information, but are designed for non-commercial, informational purposes only.
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
name: TheSkimm
provenance_date: '2026-11-10'
provider_name: TheSkimm
provider_slug: theskimm
slug: theskimm-eligibility
source_date: '2026-11-10'
source_filename: theskimm-eligibility.yml
source_heading: Eligibility
source_page: https://www.theskimm.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TheSkimm\naid: theskimm\nurl: https://www.theskimm.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Everyday Health makes no representation or warranty that the content and materials on the Sites or the Services\n    are appropriate or available for use in locations outside the United States.\nentity_types:\n- type: individual\n  text: Services are for your personal and non-commercial use.\nrestricted_uses:\n- summary: Non-commercial informational use only\n  text: The Sites and Services offer health, fitness and nutrition related information, but\
  \ are designed for non-commercial,\n    informational purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/theskimm/eligibility/theskimm-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from TheSkimm's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Media
- Newsletters
- Email
- Content
- Publishing
- Women
- Wellness
---
