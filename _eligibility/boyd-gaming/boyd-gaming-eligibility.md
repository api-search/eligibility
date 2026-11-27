---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be 21 years of age or older to use this service.
    value: '21'
  restricted_uses:
  - summary: Excluded gaming patrons not eligible for promotions
    text: Not valid for persons on a Disassociated Patrons, Voluntary Exclusion or Self Exclusion List in jurisdictions which Boyd Gaming Corporation® operates or who have been otherwise excluded from the participating property.
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
name: Boyd Gaming
provenance_date: '2026-11-09'
provider_name: Boyd Gaming
provider_slug: boyd-gaming
slug: boyd-gaming-eligibility
source_date: '2026-11-09'
source_filename: boyd-gaming-eligibility.yml
source_heading: Eligibility
source_page: https://www.boydgaming.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boyd Gaming\naid: boyd-gaming\nurl: https://www.boydgaming.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Excluded gaming patrons not eligible for promotions\n  text: Not valid for persons on a Disassociated Patrons, Voluntary Exclusion or Self Exclusion List in jurisdictions\n    which Boyd Gaming Corporation® operates or who have been otherwise excluded from the participating property.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: You\
  \ must be 21 years of age or older to use this service.\n"
source_yaml_url: https://artifacts.apis.io/boyd-gaming/eligibility/boyd-gaming-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Boyd Gaming's own page on 2026-11-09.
synthetic: false
tags:
- Gaming
- Casinos
- Hospitality
- Sports Betting
- Loyalty Programs
- Fortune 1000
---
