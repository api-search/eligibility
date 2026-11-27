---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “You” meanstheindividual accessingor usingtheService, or thecompany, or otherlegal entityonbehalf of whichsuchindividual isaccessingor usingtheService, asapplicable.
    type: individual
  minimum_age:
    text: Yourepresent that youareover theageof 18.
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
name: Twill
provenance_date: '2026-11-10'
provider_name: Twill
provider_slug: twill
slug: twill-eligibility
source_date: '2026-11-10'
source_filename: twill-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/657cbb06b30c55d98cc97f92/662047e24682cc2afb0e4e4d_Twill%20Terms%20of%20Service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Twill\naid: twill\nurl: https://cdn.prod.website-files.com/657cbb06b30c55d98cc97f92/662047e24682cc2afb0e4e4d_Twill%20Terms%20of%20Service.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “You” meanstheindividual accessingor usingtheService, or thecompany, or otherlegal entityonbehalf of whichsuchindividual\n    isaccessingor usingtheService, asapplicable.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Yourepresent that youareover theageof\
  \ 18.\n"
source_yaml_url: https://artifacts.apis.io/twill/eligibility/twill-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Twill's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Recruiting
- Hiring
- Talent
- Referrals
- HR Technology
---
