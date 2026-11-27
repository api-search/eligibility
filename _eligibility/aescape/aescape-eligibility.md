---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no claims that the Sites or any content on the Sites is accessible or appropriate outside of the United States.
  entity_types:
  - text: You must be at least 18 years of age to use the Sites.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Sites.
    value: '18'
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
name: Aescape
provenance_date: '2026-11-09'
provider_name: Aescape
provider_slug: aescape
slug: aescape-eligibility
source_date: '2026-11-09'
source_filename: aescape-eligibility.yml
source_heading: Eligibility
source_page: https://www.aescape.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aescape\naid: aescape\nurl: https://www.aescape.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no claims that the Sites or any content on the Sites is accessible or appropriate outside of the\n    United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Sites.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Sites.\n"
source_yaml_url: https://artifacts.apis.io/aescape/eligibility/aescape-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Aescape's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Robotics
- Health and Wellness
- Fitness
- Massage
- Artificial Intelligence
- Consumer Hardware
- Hospitality
- Recovery
- Identity
---
