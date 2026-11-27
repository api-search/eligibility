---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are a consumer residing in another EU country, you can submit your complaint on the EU Commission's online complaint platform
  entity_types:
  - text: '"Buyer" or "you" refers to the end user purchasing offers.'
    type: individual
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
name: happenings-social
provenance_date: '2026-11-09'
provider_name: happenings-social
provider_slug: happenings-social
slug: happenings-social-eligibility
source_date: '2026-11-09'
source_filename: happenings-social-eligibility.yml
source_heading: Eligibility
source_page: https://happenings.social/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: happenings-social\naid: happenings-social\nurl: https://happenings.social/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are a consumer residing in another EU country, you can submit your complaint on the EU Commission's\n    online complaint platform\nentity_types:\n- type: individual\n  text: '\"Buyer\" or \"you\" refers to the end user purchasing offers.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/happenings-social/eligibility/happenings-social-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from happenings-social's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social
- Event
- Platform
- Community
---
