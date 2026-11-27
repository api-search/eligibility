---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any retailer may sign up to become a Merchant by completing the information on the sign-up page of the Marsello Platform.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No purchased or rented email lists
    text: You may not use purchased or rented lists (either imported into Marsello or as part of your eCommerce store) with Marsello.
  - summary: Permission-based emails only
    text: You agree to only send Permission- based emails in connection with your use of the Services.
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
name: Marsello
provenance_date: '2026-11-10'
provider_name: Marsello
provider_slug: marsello
slug: marsello-eligibility
source_date: '2026-11-10'
source_filename: marsello-eligibility.yml
source_heading: Eligibility
source_page: https://www.marsello.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Marsello\naid: marsello\nurl: https://www.marsello.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Any retailer may sign up to become a Merchant by completing the information on the sign-up page of the Marsello\n    Platform.\nrestricted_uses:\n- summary: No purchased or rented email lists\n  text: You may not use purchased or rented lists (either imported into Marsello or as part of your eCommerce store)\n    with Marsello.\n- summary: Permission-based emails only\n  text: You agree to only send Permission- based emails in\
  \ connection with your use of the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/marsello/eligibility/marsello-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Marsello's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Loyalty
- Marketing
- Retail
- Hospitality
---
