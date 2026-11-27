---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Gridwise provides the Service for use only by persons located in the United States.
  entity_types:
  - text: If You are entering into these Terms of Service on behalf of a company or another legal entity, You represent that You have the authority to bind such entity
    type: business
  minimum_age:
    text: are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No use while driving
    text: THE SERVICE IS NOT INTENDED TO BE USED WHILE YOU ARE DRIVING OR OPERATING A VEHICLE.
  - summary: Competitors excluded
    text: are not a competitor of Gridwise or are not using the Service for reasons that are in competition with Gridwise
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
name: Gridwise
provenance_date: '2026-11-09'
provider_name: Gridwise
provider_slug: gridwise
slug: gridwise-eligibility
source_date: '2026-11-09'
source_filename: gridwise-eligibility.yml
source_heading: Eligibility
source_page: https://gridwise.io/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gridwise\naid: gridwise\nurl: https://gridwise.io/termsofservice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Gridwise provides the Service for use only by persons located in the United States.\nentity_types:\n- type: business\n  text: If You are entering into these Terms of Service on behalf of a company or another legal entity, You represent\n    that You have the authority to bind such entity\nrestricted_uses:\n- summary: No use while driving\n  text: THE SERVICE IS NOT INTENDED TO BE USED WHILE YOU ARE DRIVING OR OPERATING A VEHICLE.\n- summary: Competitors excluded\n\
  \  text: are not a competitor of Gridwise or are not using the Service for reasons that are in competition with Gridwise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/gridwise/eligibility/gridwise-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Gridwise's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gig Economy
- Rideshare
- Delivery
- Mobility Data
- Analytics
- Earnings Tracking
- Data Products
---
