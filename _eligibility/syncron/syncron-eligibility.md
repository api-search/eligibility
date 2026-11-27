---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms of Use apply to the use of our Websites and Software by natural persons.
    type: individual
  minimum_age:
    text: persons who are not of the age of majority should not be eligible to use the Websites
    value: null
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
name: Syncron
provenance_date: '2026-11-10'
provider_name: Syncron
provider_slug: syncron
slug: syncron-eligibility
source_date: '2026-11-10'
source_filename: syncron-eligibility.yml
source_heading: Eligibility
source_page: https://www.syncron.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Syncron\naid: syncron\nurl: https://www.syncron.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These Terms of Use apply to the use of our Websites and Software by natural persons.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: persons who are not of the age of majority should not be eligible to use the Websites\n"
source_yaml_url: https://artifacts.apis.io/syncron/eligibility/syncron-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Syncron's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software
- OEM
- Inventory
- Pricing
---
