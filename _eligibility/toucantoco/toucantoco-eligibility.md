---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: to allow access and use of the Solution and Application Service to Authorized Users from United States of America exclusively
  entity_types:
  - text: the customer identified in the Purchase order
    type: business
  minimum_age:
    text: null
    value: null
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
name: Toucan Toco
provenance_date: '2026-11-10'
provider_name: Toucan Toco
provider_slug: toucantoco
slug: toucantoco-eligibility
source_date: '2026-11-10'
source_filename: toucantoco-eligibility.yml
source_heading: Eligibility
source_page: https://www.toucantoco.com/en/legal-services-saas
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Toucan Toco\naid: toucantoco\nurl: https://www.toucantoco.com/en/legal-services-saas\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: to allow access and use of the Solution and Application Service to Authorized Users from United States of\n    America exclusively\nentity_types:\n- type: business\n  text: the customer identified in the Purchase order\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/toucantoco/eligibility/toucantoco-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Toucan Toco's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Business Intelligence
- Embedded Analytics
- Data Visualization
- Data Storytelling
- Dashboards
- Artificial Intelligence
---
