---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended for business and commercial audiences, including industry professionals, prospective customers, distribution partners, and research collaborators.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and embargo restrictions
    text: You represent that you are not located in a country subject to a U.S. government embargo, and that you are not listed on any U.S. government list of prohibited or restricted parties.
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
name: Moleaer
provenance_date: '2026-11-10'
provider_name: Moleaer
provider_slug: moleaer
slug: moleaer-eligibility
source_date: '2026-11-10'
source_filename: moleaer-eligibility.yml
source_heading: Eligibility
source_page: https://www.moleaer.com/en-us/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moleaer\naid: moleaer\nurl: https://www.moleaer.com/en-us/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Site is intended for business and commercial audiences, including industry professionals, prospective\n    customers, distribution partners, and research collaborators.\nrestricted_uses:\n- summary: Export and embargo restrictions\n  text: You represent that you are not located in a country subject to a U.S. government embargo, and that you are\n    not listed on any U.S. government list of prohibited or restricted\
  \ parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/moleaer/eligibility/moleaer-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Moleaer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Nanobubbles
- Water Treatment
- Water Quality
- Aquaculture
- Agriculture
- Wastewater
- Industrial Equipment
- Remote Monitoring
- IoT
- Manufacturing
---
