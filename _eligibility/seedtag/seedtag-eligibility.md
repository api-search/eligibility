---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Access to and use of the Website is only permitted to persons over eighteen (18) years of age.
    type: individual
  minimum_age:
    text: Access to and use of the Website is only permitted to persons over eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: No unlawful purpose
    text: You shall not use the Website for any unlawful purpose.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Access to and use of the Website does not require the creation of a user account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Seedtag
provenance_date: '2026-11-10'
provider_name: Seedtag
provider_slug: seedtag
slug: seedtag-eligibility
source_date: '2026-11-10'
source_filename: seedtag-eligibility.yml
source_heading: Eligibility
source_page: https://www.seedtag.com/legal-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Seedtag\naid: seedtag\nurl: https://www.seedtag.com/legal-notice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Access to and use of the Website is only permitted to persons over eighteen (18) years of age.\nrestricted_uses:\n- summary: No unlawful purpose\n  text: You shall not use the Website for any unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Access to and use of the Website does not require the creation of a user account.\nminimum_age:\n  value: '18'\n  text: Access to and use\
  \ of the Website is only permitted to persons over eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/seedtag/eligibility/seedtag-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Seedtag's own page on 2026-11-10.
synthetic: false
tags:
- Contextual Advertising
- AdTech
- Displays
- Video
- Publishers
- Advertisers
---
