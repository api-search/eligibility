---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is not intended for use outside the United States.
  entity_types:
  - text: You must be at least EIGHTEEN (18) YEARS OF AGE to register as a user of the Site or access the Services.
    type: individual
  minimum_age:
    text: You must be at least EIGHTEEN (18) YEARS OF AGE to register as a user of the Site or access the Services.
    value: '18'
  restricted_uses:
  - summary: Ticket resale
    text: Tickets purchased through the Site or Services are for personal use only and may not be resold for commercial purposes or at a price above face value plus applicable fees without Cosm’s express written consent.
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
name: Cosm
provenance_date: '2026-11-09'
provider_name: Cosm
provider_slug: cosm
slug: cosm-eligibility
source_date: '2026-11-09'
source_filename: cosm-eligibility.yml
source_heading: Eligibility
source_page: https://www.cosm.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cosm\naid: cosm\nurl: https://www.cosm.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site is not intended for use outside the United States.\nentity_types:\n- type: individual\n  text: You must be at least EIGHTEEN (18) YEARS OF AGE to register as a user of the Site or access the Services.\nrestricted_uses:\n- summary: Ticket resale\n  text: Tickets purchased through the Site or Services are for personal use only and may not be resold for commercial\n    purposes or at a price above face value plus applicable fees without Cosm’s express written consent.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least EIGHTEEN (18) YEARS OF AGE to register as a user of the Site or access the Services.\n"
source_yaml_url: https://artifacts.apis.io/cosm/eligibility/cosm-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cosm's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Immersive Experiences
- Entertainment
- Media
- Sports
- Venues
- Display Technology
- Planetarium
- Content Production
---
