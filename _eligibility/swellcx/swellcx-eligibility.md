---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: personal, non-exclusive, non-transferable (except as permitted under Section 11.3), non-sublicensable license in the United States
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No competitors as Authorized Users
    text: Authorized Users may not include competitors of Swell.
  - summary: Patients are not Authorized Users
    text: Patients are not Authorized Users.
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
name: Swell
provenance_date: '2026-11-10'
provider_name: Swell
provider_slug: swellcx
slug: swellcx-eligibility
source_date: '2026-11-10'
source_filename: swellcx-eligibility.yml
source_heading: Eligibility
source_page: https://www.swellcx.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Swell\naid: swellcx\nurl: https://www.swellcx.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: personal, non-exclusive, non-transferable (except as permitted under Section 11.3), non-sublicensable license\n    in the United States\nentity_types: []\nrestricted_uses:\n- summary: No competitors as Authorized Users\n  text: Authorized Users may not include competitors of Swell.\n- summary: Patients are not Authorized Users\n  text: Patients are not Authorized Users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/swellcx/eligibility/swellcx-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Swell's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Healthcare
- Reputation
- Patient Experience
---
