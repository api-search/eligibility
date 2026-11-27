---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to be eligible to use the Site. However, if you are at least 13 years old but not yet 18, you may use the Site in conjunction with your parent or guardian who agrees to this Agreement.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to be eligible to use the Site.
    value: '18'
  restricted_uses:
  - summary: No advertising or solicitation
    text: End User shall not use this Site to advertise or perform any commercial, religious, political or non-commercial solicitation
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
name: Enervee
provenance_date: '2026-11-09'
provider_name: Enervee
provider_slug: enervee
slug: enervee-eligibility
source_date: '2026-11-09'
source_filename: enervee-eligibility.yml
source_heading: Eligibility
source_page: https://www.enervee.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enervee\naid: enervee\nurl: https://www.enervee.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to be eligible to use the Site. However, if you are at least 13 years\n    old but not yet 18, you may use the Site in conjunction with your parent or guardian who agrees to this Agreement.\nrestricted_uses:\n- summary: No advertising or solicitation\n  text: End User shall not use this Site to advertise or perform any commercial, religious, political or non-commercial\n    solicitation\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to be eligible to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/enervee/eligibility/enervee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Enervee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Energy Efficiency
- Marketplace
- Utilities
- Sustainability
- Climate
- Embedded Finance
---
