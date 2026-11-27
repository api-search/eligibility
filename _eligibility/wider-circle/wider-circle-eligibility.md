---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Text messaging is supported in the United States only. Users represent they are not located in a country subject to a U.S. Government embargo or sanctions program.
  minimum_age:
    text: you represent that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Prohibited activities
    text: You may not engage in any of the following with regard to the Service
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
name: Wider Circle
provenance_date: '2026-11-10'
provider_name: Wider Circle
provider_slug: wider-circle
slug: wider-circle-eligibility
source_date: '2026-11-10'
source_filename: wider-circle-eligibility.yml
source_heading: Eligibility
source_page: https://www.widercircle.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wider Circle\naid: wider-circle\nurl: https://www.widercircle.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Text messaging is supported in the United States only. Users represent they are not located in a country\n    subject to a U.S. Government embargo or sanctions program.\nentity_types: []\nrestricted_uses:\n- summary: Prohibited activities\n  text: You may not engage in any of the following with regard to the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you\
  \ are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/wider-circle/eligibility/wider-circle-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Wider Circle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health Plans
- Medicare Advantage
- Medicaid
- Population Health
- Social Determinants of Health
- Member Engagement
- Care Coordination
- Community Health
---
