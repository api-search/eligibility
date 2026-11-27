---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you reside in Canada, any disputes arising out of or related to these Terms of Use ... shall be governed by the laws of the Province in which you reside
  entity_types:
  - text: You have reached the age of majority in the state or province in which you reside; You are able to create a binding legal obligation;
    type: individual
  minimum_age:
    text: You have reached the age of majority in the state or province in which you reside;
    value: age of majority
  restricted_uses:
  - summary: Adults only
    text: The Site is designed and intended for adults.
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
name: Groupon
provenance_date: '2026-11-09'
provider_name: Groupon
provider_slug: groupon
slug: groupon-eligibility
source_date: '2026-11-09'
source_filename: groupon-eligibility.yml
source_heading: Eligibility
source_page: https://www.groupon.com/legal/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Groupon\naid: groupon\nurl: https://www.groupon.com/legal/termsofservice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you reside in Canada, any disputes arising out of or related to these Terms of Use ... shall be governed\n    by the laws of the Province in which you reside\nentity_types:\n- type: individual\n  text: You have reached the age of majority in the state or province in which you reside; You are able to create\n    a binding legal obligation;\nrestricted_uses:\n- summary: Adults only\n  text: The Site is designed and intended for adults.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You have reached the age of majority in the state or province in which you reside;\n"
source_yaml_url: https://artifacts.apis.io/groupon/eligibility/groupon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Groupon's own page on 2026-11-09.
synthetic: false
tags:
- Fortune 1000
- Local Commerce
- Marketplace
- E-Commerce
- Deals
- Booking
- Reservations
- Travel
- Retail
---
