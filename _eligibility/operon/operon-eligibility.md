---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the organization that subscribes to our Services (the "Customer")
    type: business
  - text: each person who uses them (a "User")
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Invitation only. Access is by invitation from Operon or from a Customer's workspace owner.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Operon
provenance_date: '2026-11-10'
provider_name: Operon
provider_slug: operon
slug: operon-eligibility
source_date: '2026-11-10'
source_filename: operon-eligibility.yml
source_heading: Eligibility
source_page: https://www.operonsolutions.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Operon\naid: operon\nurl: https://www.operonsolutions.com/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the organization that subscribes to our Services (the \"Customer\")\n- type: individual\n  text: each person who uses them (a \"User\")\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Invitation only. Access is by invitation from Operon or from a Customer's workspace owner.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/operon/eligibility/operon-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from Operon's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Manufacturing
- Industrial
- Engineering
- Artificial Intelligence
- P&ID
- Process Industries
- Chemical Engineering
- Data Intelligence
- DEXPI
---
