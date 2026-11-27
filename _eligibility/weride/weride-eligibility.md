---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 18 years of age (not limited to those who are over 16 years of age and whose main source of income is their own labor income), please read this agreement with the accompaniment of your parents or other legal guardians
    type: individual
  minimum_age:
    text: If you are under 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful content
    text: Do not upload, display, or disseminate any false, harassing, defamatory, abusive, threatening, vulgar, obscene, or any other illegal information or data
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
name: WeRide
provenance_date: '2026-11-10'
provider_name: WeRide
provider_slug: weride
slug: weride-eligibility
source_date: '2026-11-10'
source_filename: weride-eligibility.yml
source_heading: Eligibility
source_page: https://weride.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WeRide\naid: weride\nurl: https://weride.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 18 years of age (not limited to those who are over 16 years of age and whose main source\n    of income is their own labor income), please read this agreement with the accompaniment of your parents or other\n    legal guardians\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Do not upload, display, or disseminate any false, harassing, defamatory, abusive, threatening, vulgar, obscene,\n    or any other\
  \ illegal information or data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/weride/eligibility/weride-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from WeRide's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Autonomous Driving
- Robotaxi
- Self-Driving
- Mobility
- Transportation
- ADAS
- Logistics
---
