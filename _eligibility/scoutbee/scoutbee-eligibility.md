---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Scoutbee provides its Services exclusively to entrepreneurs within the meaning of Section 14 of the German Civil Code (BGB).
  entity_types:
  - text: Scoutbee provides its Services exclusively to entrepreneurs within the meaning of Section 14 of the German Civil Code (BGB).
    type: business
  - text: '" Buyer " means any individual or entity that is purchasing access to the Services.'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited AI uses
    text: use AI for high-risk applications (e.g., health advice, legal guidance, financial advice) without human oversight.
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
name: Scoutbee
provenance_date: '2026-11-10'
provider_name: Scoutbee
provider_slug: scoutbee
slug: scoutbee-eligibility
source_date: '2026-11-10'
source_filename: scoutbee-eligibility.yml
source_heading: Eligibility
source_page: https://www.scoutbee.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scoutbee\naid: scoutbee\nurl: https://www.scoutbee.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Scoutbee provides its Services exclusively to entrepreneurs within the meaning of Section 14 of the German\n    Civil Code (BGB).\nentity_types:\n- type: business\n  text: Scoutbee provides its Services exclusively to entrepreneurs within the meaning of Section 14 of the German\n    Civil Code (BGB).\n- type: individual\n  text: '\" Buyer \" means any individual or entity that is purchasing access to the Services.'\nrestricted_uses:\n- summary: Prohibited AI\
  \ uses\n  text: use AI for high-risk applications (e.g., health advice, legal guidance, financial advice) without human\n    oversight.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/scoutbee/eligibility/scoutbee-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Scoutbee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Enterprise Software
- Procurement
- Supplier Discovery
- Supply Chain
- Sourcing
- Artificial Intelligence
- Enterprise Software
---
