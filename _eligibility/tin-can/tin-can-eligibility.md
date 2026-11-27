---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - AU
    - CA
    text: Use of our Products or Services is currently authorized only in the United States, Australia, and Canada.
  entity_types:
  - text: You may only use our Products and Services for personal, family or household purposes and expressly excluding any commercial use.
    type: individual
  minimum_age:
    text: Users under 18 years of age are not permitted to use the Services.
    value: '18'
  restricted_uses:
  - summary: Commercial telemarketing or pre-recorded calls
    text: Engage in any telemarketing, debt-collection, or other calls with a commercial purpose, or make any pre-recorded or artificial voice calls;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must create an account with Tin Can in order to use some or all of our Products and Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tin Can
provenance_date: '2026-11-10'
provider_name: Tin Can
provider_slug: tin-can
slug: tin-can-eligibility
source_date: '2026-11-10'
source_filename: tin-can-eligibility.yml
source_heading: Eligibility
source_page: https://tincan.kids/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tin Can\naid: tin-can\nurl: https://tincan.kids/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - AU\n  - CA\n  excluded: []\n  text: Use of our Products or Services is currently authorized only in the United States, Australia, and Canada.\nentity_types:\n- type: individual\n  text: You may only use our Products and Services for personal, family or household purposes and expressly excluding\n    any commercial use.\nrestricted_uses:\n- summary: Commercial telemarketing or pre-recorded calls\n  text: Engage in any telemarketing, debt-collection, or other\
  \ calls with a commercial purpose, or make any pre-recorded\n    or artificial voice calls;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must create an account with Tin Can in order to use some or all of our Products and Services.\nminimum_age:\n  value: '18'\n  text: Users under 18 years of age are not permitted to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/tin-can/eligibility/tin-can-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Tin Can's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Hardware
- Telecommunications
- Voice
- Kids
- Phone
---
