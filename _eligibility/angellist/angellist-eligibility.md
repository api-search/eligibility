---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is not directed to any person in any jurisdiction where (by reason of that person’s nationality, residence or otherwise) the publication or availability of the Site is prohibited.
  entity_types:
  - text: you are at least 18 years old
    type: individual
  - text: You agree that you have the right, authority, and capacity to enter into the Terms on your own behalf and on behalf of any entity or third party for whom you are acting
    type: business
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Commercial or investment use of Content
    text: use any Content, or other information acquired from AngelList Parties, Users, the Site or otherwise through your use of the Services for commercial or investment activity or purpose outside of the purposes for which we make the Services available
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: AngelList does not inquire into the backgrounds of its Users or attempt to verify the Content provided by its Users (although it reserves the right to conduct any background check or other screening at any time using available public sources).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AngelList
provenance_date: '2026-11-09'
provider_name: AngelList
provider_slug: angellist
slug: angellist-eligibility
source_date: '2026-11-09'
source_filename: angellist-eligibility.yml
source_heading: Eligibility
source_page: https://venture.angellist.com/v/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AngelList\naid: angellist\nurl: https://venture.angellist.com/v/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Site is not directed to any person in any jurisdiction where (by reason of that person’s nationality,\n    residence or otherwise) the publication or availability of the Site is prohibited.\nentity_types:\n- type: individual\n  text: you are at least 18 years old\n- type: business\n  text: You agree that you have the right, authority, and capacity to enter into the Terms on your own behalf and\n    on behalf of any entity or third party\
  \ for whom you are acting\nrestricted_uses:\n- summary: Commercial or investment use of Content\n  text: use any Content, or other information acquired from AngelList Parties, Users, the Site or otherwise through\n    your use of the Services for commercial or investment activity or purpose outside of the purposes for which\n    we make the Services available\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: AngelList does not inquire into the backgrounds of its Users or attempt to verify the Content provided by\n    its Users (although it reserves the right to conduct any background check or other screening at any time using\n    available public sources).\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/angellist/eligibility/angellist-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from AngelList's own page on 2026-11-09.
synthetic: false
tags:
- Documents
- Fund
- Investing
- Job
- Startups
- Transaction
- Venture Capital
- A2A
---
