---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Most SmartSign products can be shipped to all U.S. addresses, including Puerto Rico, the Virgin Islands, and APO/FPO addresses.
  entity_types:
  - text: Purchase order (PO) billing is available for approved business customers and is subject to credit review.
    type: business
  minimum_age:
    text: The Site is not intended for minors under the age of 18.
    value: '18'
  restricted_uses:
  - summary: No spam
    text: You agree you will not use the Site to send unsolicited bulk messages ("spam").
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
name: Smartsign
provenance_date: '2026-11-10'
provider_name: Smartsign
provider_slug: smartsign
slug: smartsign-eligibility
source_date: '2026-11-10'
source_filename: smartsign-eligibility.yml
source_heading: Eligibility
source_page: https://www.smartsign.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Smartsign\naid: smartsign\nurl: https://www.smartsign.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Most SmartSign products can be shipped to all U.S. addresses, including Puerto Rico, the Virgin Islands,\n    and APO/FPO addresses.\nentity_types:\n- type: business\n  text: Purchase order (PO) billing is available for approved business customers and is subject to credit review.\nrestricted_uses:\n- summary: No spam\n  text: You agree you will not use the Site to send unsolicited bulk messages (\"spam\").\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is not intended for minors under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/smartsign/eligibility/smartsign-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Smartsign's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Signage
- E-Commerce
- Labels
- Safety
- Compliance
- Retail
- Printing
---
