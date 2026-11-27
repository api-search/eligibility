---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: BY ACCESSING OR USING THE SITES, YOU ARE ACCEPTING THESE TERMS (ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT)
    type: individual
  minimum_age:
    text: If you are under 18 years of age you are not permitted to access such content.
    value: '18'
  restricted_uses:
  - summary: Mature content age limit
    text: If you are under 18 years of age you are not permitted to access such content.
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
name: Bookbub
provenance_date: '2026-11-09'
provider_name: Bookbub
provider_slug: bookbub
slug: bookbub-eligibility
source_date: '2026-11-09'
source_filename: bookbub-eligibility.yml
source_heading: Eligibility
source_page: https://www.bookbub.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bookbub\naid: bookbub\nurl: https://www.bookbub.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: BY ACCESSING OR USING THE SITES, YOU ARE ACCEPTING THESE TERMS (ON BEHALF OF YOURSELF OR THE ENTITY THAT\n    YOU REPRESENT)\nrestricted_uses:\n- summary: Mature content age limit\n  text: If you are under 18 years of age you are not permitted to access such content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age you are not\
  \ permitted to access such content.\n"
source_yaml_url: https://artifacts.apis.io/bookbub/eligibility/bookbub-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bookbub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Books
- Publishing
- Ebooks
- Reading
- Book Discovery
- Author Marketing
- Advertising
- Media
- Consumer
---
