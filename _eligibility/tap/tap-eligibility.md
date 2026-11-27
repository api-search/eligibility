---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We are based in the United States and the Services are intended for users located in the United States.
  entity_types:
  - text: By using the Services, you represent that you are at least 18 years of age.
    type: individual
  minimum_age:
    text: By using the Services, you represent that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: AI assessment age limit
    text: Our AI-powered assessment services are strictly limited to individuals who are 18 years of age or older.
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
name: Tap
provenance_date: '2026-11-10'
provider_name: Tap
provider_slug: tap
slug: tap-eligibility
source_date: '2026-11-10'
source_filename: tap-eligibility.yml
source_heading: Eligibility
source_page: https://www.tap3d.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tap\naid: tap\nurl: https://www.tap3d.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We are based in the United States and the Services are intended for users located in the United States.\nentity_types:\n- type: individual\n  text: By using the Services, you represent that you are at least 18 years of age.\nrestricted_uses:\n- summary: AI assessment age limit\n  text: Our AI-powered assessment services are strictly limited to individuals who are 18 years of age or older.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: By using the Services, you represent that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/tap/eligibility/tap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Training
- Manufacturing
- Virtual Reality
- Workforce Development
- Education
- Skills Assessment
- E-Learning
---
