---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Users under the age of 18 are only permitted to access and use the Website while under the direct supervision of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Minors need supervision
    text: Users under the age of 18 are only permitted to access and use the Website while under the direct supervision of a parent or guardian.
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
name: Venue
provenance_date: '2026-11-10'
provider_name: Venue
provider_slug: venue
slug: venue-eligibility
source_date: '2026-11-10'
source_filename: venue-eligibility.yml
source_heading: Eligibility
source_page: https://www.venue.live/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Venue\naid: venue\nurl: https://www.venue.live/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Minors need supervision\n  text: Users under the age of 18 are only permitted to access and use the Website while under the direct supervision\n    of a parent or guardian.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users under the age of 18 are only permitted to access and use the Website while under the direct supervision\n    of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/venue/eligibility/venue-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Venue's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Productivity
- Internal Communications
- Video
- Webinars
- Event
- Live Streaming
---
