---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We operate the Service from our offices in California, and we make no representation that Materials included in the Service are appropriate or available for use in other locations.
  entity_types:
  - text: You must be at least 18 years old or have the consent of your parent or guardian to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old or have the consent of your parent or guardian to use our Services.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: Use our Services for any illegal or unauthorized purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access and use the Platform, Customer shall be required to register for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Twisty
provenance_date: '2026-11-10'
provider_name: Twisty
provider_slug: twisty
slug: twisty-eligibility
source_date: '2026-11-10'
source_filename: twisty-eligibility.yml
source_heading: Eligibility
source_page: https://twisty.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Twisty\naid: twisty\nurl: https://twisty.ai/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We operate the Service from our offices in California, and we make no representation that Materials included\n    in the Service are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or have the consent of your parent or guardian to use our Services.\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: Use our Services for any illegal or unauthorized purpose.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: To access and use the Platform, Customer shall be required to register for an account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or have the consent of your parent or guardian to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/twisty/eligibility/twisty-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Twisty's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- Content Creation
- AI Characters
- Media
- Consumer
---
