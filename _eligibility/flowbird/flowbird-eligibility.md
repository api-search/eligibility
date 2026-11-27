---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The site or certain sections of it are available using an access code and password that will be provided by Flowbird.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Flowbird
provenance_date: '2026-11-09'
provider_name: Flowbird
provider_slug: flowbird
slug: flowbird-eligibility
source_date: '2026-11-09'
source_filename: flowbird-eligibility.yml
source_heading: Eligibility
source_page: https://www.flowbird.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flowbird\naid: flowbird\nurl: https://www.flowbird.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The site or certain sections of it are available using an access code and password that will be provided\n    by Flowbird.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flowbird/eligibility/flowbird-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Flowbird's own page on 2026-11-09.
synthetic: false
tags:
- Parking
- Urban Mobility
- Transit Ticketing
- Payments
- Smart City
- Pay Stations
- EV Charging
- Digital Permits
---
