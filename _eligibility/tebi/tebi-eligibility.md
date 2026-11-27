---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual or entity subscribing to a Tebi product (“Customer”)
    type: individual
  - text: the individual or entity subscribing to a Tebi product (“Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal business use only
    text: use the Products for any use other than Customer’s internal business use
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
name: Tebi
provenance_date: '2026-11-10'
provider_name: Tebi
provider_slug: tebi
slug: tebi-eligibility
source_date: '2026-11-10'
source_filename: tebi-eligibility.yml
source_heading: Eligibility
source_page: https://www.tebi.com/privacy/tebi-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tebi\naid: tebi\nurl: https://www.tebi.com/privacy/tebi-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the individual or entity subscribing to a Tebi product (“Customer”)\n- type: business\n  text: the individual or entity subscribing to a Tebi product (“Customer”)\nrestricted_uses:\n- summary: Internal business use only\n  text: use the Products for any use other than Customer’s internal business use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n \
  \ text: null\n"
source_yaml_url: https://artifacts.apis.io/tebi/eligibility/tebi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Tebi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Point-of-Sale
- Hospitality
- Restaurant
- Reservations
- Inventory
- CRM
---
