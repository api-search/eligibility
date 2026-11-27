---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Rewards Program (the “Program”) is open to legal residents of Florida, USA
  entity_types:
  - text: open to legal residents of Florida, USA, who are 18 years of age or older at the time of enrollment
    type: individual
  minimum_age:
    text: 18 years of age or older at the time of enrollment
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Participants must have a valid Florida mailing address to be eligible for the Program.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Velocia
provenance_date: '2026-11-10'
provider_name: Velocia
provider_slug: velocia
slug: velocia-eligibility
source_date: '2026-11-10'
source_filename: velocia-eligibility.yml
source_heading: Eligibility
source_page: https://velocia.io/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Velocia\naid: velocia\nurl: https://velocia.io/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Rewards Program (the “Program”) is open to legal residents of Florida, USA\nentity_types:\n- type: individual\n  text: open to legal residents of Florida, USA, who are 18 years of age or older at the time of enrollment\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Participants must have a valid Florida mailing address to be eligible for the Program.\nminimum_age:\n  value: '18'\n  text: 18 years of age or\
  \ older at the time of enrollment\n"
source_yaml_url: https://artifacts.apis.io/velocia/eligibility/velocia-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Velocia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mobility
- Transit
- Rewards
- Incentives
- Public Transportation
- Smart Cities
- Loyalty & Incentives
---
