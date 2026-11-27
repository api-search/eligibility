---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Customer shall use the Services solely for its business purposes as contemplated by this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: (15) use the Services or the Content for any illegal or unauthorized purpose.
  - summary: Harassment or defamation
    text: (14) use the Services to harass, defame, slander, or intimidate;
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
name: Strada
provenance_date: '2026-11-09'
provider_name: Strada
provider_slug: getstrada
slug: getstrada-eligibility
source_date: '2026-11-09'
source_filename: getstrada-eligibility.yml
source_heading: Eligibility
source_page: https://www.getstrada.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Strada\naid: getstrada\nurl: https://www.getstrada.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Customer shall use the Services solely for its business purposes as contemplated by this Agreement.\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: (15) use the Services or the Content for any illegal or unauthorized purpose.\n- summary: Harassment or defamation\n  text: (14) use the Services to harass, defame, slander, or intimidate;\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/getstrada/eligibility/getstrada-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Strada's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Insurance
- Automation
- Platform
---
