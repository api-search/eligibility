---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website is operated from the United States and is intended for users in the United States.
  entity_types:
  - text: Our Services are intended for Companies seeking more information about Bestow and the solutions we can provide to such Companies.
    type: business
  minimum_age:
    text: such individuals representing such Companies must be at least eighteen (18) years old or have otherwise reached the age of majority in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: No unsolicited commercial communications
    text: use the Service to perform any unsolicited commercial communication not permitted by applicable law
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
name: Bestow
provenance_date: '2026-11-09'
provider_name: Bestow
provider_slug: bestow
slug: bestow-eligibility
source_date: '2026-11-09'
source_filename: bestow-eligibility.yml
source_heading: Eligibility
source_page: https://www.bestow.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bestow\naid: bestow\nurl: https://www.bestow.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website is operated from the United States and is intended for users in the United States.\nentity_types:\n- type: business\n  text: Our Services are intended for Companies seeking more information about Bestow and the solutions we can provide\n    to such Companies.\nrestricted_uses:\n- summary: No unsolicited commercial communications\n  text: use the Service to perform any unsolicited commercial communication not permitted by applicable law\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: such individuals representing such Companies must be at least eighteen (18) years old or have otherwise\n    reached the age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/bestow/eligibility/bestow-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bestow's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Life Insurance
- Insurtech
- Embedded Insurance
- Insurance As A Service
- Underwriting
- Policy Administration
- Term Life
- Final Expense
- IUL
- Protect API
- SDK
- ACORD
- Financial Services
---
