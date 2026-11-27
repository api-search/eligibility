---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Only available to U.S. customers leasing through Lucid Financial Services.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Offer available to well-qualified lessees only.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lucid Motors
provenance_date: '2026-11-09'
provider_name: Lucid Motors
provider_slug: lucid-motors
slug: lucid-motors-eligibility
source_date: '2026-11-09'
source_filename: lucid-motors-eligibility.yml
source_heading: Eligibility
source_page: https://lucidmotors.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lucid Motors\naid: lucid-motors\nurl: https://lucidmotors.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Only available to U.S. customers leasing through Lucid Financial Services.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Offer available to well-qualified lessees only.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lucid-motors/eligibility/lucid-motors-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Lucid Motors's own page on 2026-11-09.
synthetic: false
tags:
- Automotive
- Electric Vehicles
- Luxury Vehicles
- Connected Vehicles
- Battery Technology
- Powertrain
- Manufacturing
- Over-the-Air Updates
- Mobile App
- Lucid Air
- Lucid Gravity
- NASDAQ
---
