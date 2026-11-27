---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is only intended for individuals aged eighteen (18) years or older.
    type: individual
  minimum_age:
    text: The Website is only intended for individuals aged eighteen (18) years or older.
    value: '18'
  restricted_uses:
  - summary: Unauthorized commercial communications
    text: You agree not to, and will not, use the communication systems provided by the Website to send unauthorized commercial communications
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
name: Island
provenance_date: '2026-11-09'
provider_name: Island
provider_slug: island
slug: island-eligibility
source_date: '2026-11-09'
source_filename: island-eligibility.yml
source_heading: Eligibility
source_page: https://www.island.io/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Island\naid: island\nurl: https://www.island.io/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is only intended for individuals aged eighteen (18) years or older.\nrestricted_uses:\n- summary: Unauthorized commercial communications\n  text: You agree not to, and will not, use the communication systems provided by the Website to send unauthorized\n    commercial communications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website\
  \ is only intended for individuals aged eighteen (18) years or older.\n"
source_yaml_url: https://artifacts.apis.io/island/eligibility/island-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Island's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Enterprise Browser
- Zero Trust
- SASE
- Data Protection
- Privileged Access Management
- Insider Risk
- Web Security
- AI Security
---
