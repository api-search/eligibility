---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: individual
  minimum_age:
    text: You represent that you are at least 18 years old. The Company does not permit those under 18 to use the Service.
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
name: SecondSight
provenance_date: '2026-11-10'
provider_name: SecondSight
provider_slug: secondsight
slug: secondsight-eligibility
source_date: '2026-11-10'
source_filename: secondsight-eligibility.yml
source_heading: Eligibility
source_page: https://www.secondsight.ai/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SecondSight\naid: secondsight\nurl: https://www.secondsight.ai/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 years old. The Company does not permit those under 18 to use the\n\
  \    Service.\n"
source_yaml_url: https://artifacts.apis.io/secondsight/eligibility/secondsight-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from SecondSight's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurance
- Cyber Insurance
- Insurtech
- Risk Management
- Cybersecurity
- Underwriting
- Artificial Intelligence
- Analytics
---
