---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any individual of legal age or capacity who wishes to use the Web Site
    type: individual
  minimum_age:
    text: any individual of legal age or capacity who wishes to use the Web Site
    value: null
  restricted_uses:
  - summary: Non-commercial personal use
    text: Use of the Site is limited to personal, non-business or commercial purposes.
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
name: Worldia
provenance_date: '2026-11-10'
provider_name: Worldia
provider_slug: worldia
slug: worldia-eligibility
source_date: '2026-11-10'
source_filename: worldia-eligibility.yml
source_heading: Eligibility
source_page: https://corp.worldia.com/hubfs/website%20-%20v3/legal/terms-of-use-EN.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Worldia\naid: worldia\nurl: https://corp.worldia.com/hubfs/website%20-%20v3/legal/terms-of-use-EN.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: any individual of legal age or capacity who wishes to use the Web Site\nrestricted_uses:\n- summary: Non-commercial personal use\n  text: Use of the Site is limited to personal, non-business or commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: any individual of legal age or capacity who wishes to\
  \ use the Web Site\n"
source_yaml_url: https://artifacts.apis.io/worldia/eligibility/worldia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Worldia's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Tourism
- Booking
- Trip Planning
- Travel Technology
- Hospitality
- B2B2C
- White Label
- Itinerary
- Distribution
---
