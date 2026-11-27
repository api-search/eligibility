---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to use this Service.
    value: '13'
  restricted_uses:
  - summary: Prohibited uses
    text: 'You agree not to use the Service to: Violate any applicable laws or regulations; infringe upon the rights of others'
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
name: Aitrips.io
provenance_date: '2026-11-09'
provider_name: Aitrips.io
provider_slug: aitrips-io
slug: aitrips-io-eligibility
source_date: '2026-11-09'
source_filename: aitrips-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.aitrips.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aitrips.io\naid: aitrips-io\nurl: https://www.aitrips.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses\n  text: 'You agree not to use the Service to: Violate any applicable laws or regulations; infringe upon the rights\n    of others'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use this Service.\n"
source_yaml_url: https://artifacts.apis.io/aitrips-io/eligibility/aitrips-io-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Aitrips.io's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Mapping
- Trip Planning
- Artificial Intelligence
- Transportation
- Weather
---
