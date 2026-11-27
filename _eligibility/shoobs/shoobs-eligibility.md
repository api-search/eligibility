---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: The Site is intended for use by persons who are ordinarily resident in the United Kingdom.
  entity_types:
  - text: where the Event Promoter is a body corporate, partnership or trust, the Event Promoter must be properly incorporated and/or constituted
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-personal ticket purchases
    text: The User may not purchase Tickets as part of any form of business or commercial activity
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
name: Shoobs
provenance_date: '2026-11-10'
provider_name: Shoobs
provider_slug: shoobs
slug: shoobs-eligibility
source_date: '2026-11-10'
source_filename: shoobs-eligibility.yml
source_heading: Eligibility
source_page: https://shoobs.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shoobs\naid: shoobs\nurl: https://shoobs.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: The Site is intended for use by persons who are ordinarily resident in the United Kingdom.\nentity_types:\n- type: business\n  text: where the Event Promoter is a body corporate, partnership or trust, the Event Promoter must be properly\n    incorporated and/or constituted\nrestricted_uses:\n- summary: Non-personal ticket purchases\n  text: The User may not purchase Tickets as part of any form of business or commercial activity\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shoobs/eligibility/shoobs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Shoobs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Event
- Ticketing
- Entertainment
- Nightlife
- Music
- Discovery
- Consumer
---
