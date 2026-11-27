---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services should only be used in a business or commercial setting and is not intended for personal use.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Embargoed countries and designated nationals
    text: Use of the Service is representation and warranty that the user is not located in, under the control of, or a national or resident of an Embargoed Country or Designated National.
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
name: Partender
provenance_date: '2026-11-10'
provider_name: Partender
provider_slug: partender
slug: partender-eligibility
source_date: '2026-11-10'
source_filename: partender-eligibility.yml
source_heading: Eligibility
source_page: https://app.partender.com/#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Partender\naid: partender\nurl: https://app.partender.com/#terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services should only be used in a business or commercial setting and is not intended for personal use.\nrestricted_uses:\n- summary: Embargoed countries and designated nationals\n  text: Use of the Service is representation and warranty that the user is not located in, under the control of,\n    or a national or resident of an Embargoed Country or Designated National.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/partender/eligibility/partender-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Partender's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Bar Inventory
- Hospitality
- Restaurant
- Inventory
- Beverages
- Point-of-Sale
- Ordering
---
