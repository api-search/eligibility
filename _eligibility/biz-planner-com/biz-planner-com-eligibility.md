---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use of the Site and Services is permitted for legitimate personal and business purposes only (including business purchase of services).
    type: business
  minimum_age:
    text: Use of the Site and Services is permitted from age 18 and above only.
    value: '18'
  restricted_uses:
  - summary: AI misuse
    text: Questions unrelated to business planning (requests for code writing, poetry, jokes, etc.)
  - summary: AI commercial use
    text: Commercial use or direct competition
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
name: BizPlanner
provenance_date: '2026-11-09'
provider_name: BizPlanner
provider_slug: biz-planner-com
slug: biz-planner-com-eligibility
source_date: '2026-11-09'
source_filename: biz-planner-com-eligibility.yml
source_heading: Eligibility
source_page: https://biz-planner.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BizPlanner\naid: biz-planner-com\nurl: https://biz-planner.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Use of the Site and Services is permitted for legitimate personal and business purposes only (including\n    business purchase of services).\nrestricted_uses:\n- summary: AI misuse\n  text: Questions unrelated to business planning (requests for code writing, poetry, jokes, etc.)\n- summary: AI commercial use\n  text: Commercial use or direct competition\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: Use of the Site and Services is permitted from age 18 and above only.\n"
source_yaml_url: https://artifacts.apis.io/biz-planner-com/eligibility/biz-planner-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BizPlanner's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Artificial Intelligence
- Simulation
- Entrepreneurship
- Software-as-a-Service
---
