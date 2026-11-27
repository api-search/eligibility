---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Nombor TIN & Nombor SST (jika melibatkan syarikat perniagaan)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Single couple per package
    text: Pakej promosi perkahwinan di Rumah Abang Jamil hanya untuk satu (1) pasangan pengantin sahaja.
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
name: Nikahsatu
provenance_date: '2026-11-10'
provider_name: Nikahsatu
provider_slug: nikahsatu
slug: nikahsatu-eligibility
source_date: '2026-11-10'
source_filename: nikahsatu-eligibility.yml
source_heading: Eligibility
source_page: https://nikahsatu.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nikahsatu\naid: nikahsatu\nurl: https://nikahsatu.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Nombor TIN & Nombor SST (jika melibatkan syarikat perniagaan)\nrestricted_uses:\n- summary: Single couple per package\n  text: Pakej promosi perkahwinan di Rumah Abang Jamil hanya untuk satu (1) pasangan pengantin sahaja.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nikahsatu/eligibility/nikahsatu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Nikahsatu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Weddings
- Marketplace
- Event
- E-Commerce
- Malaysia
- Consumer
---
