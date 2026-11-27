---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years of age to use this website.
    type: individual
  minimum_age:
    text: You must be at least 13 years of age to use this website.
    value: '13'
  restricted_uses:
  - summary: Unlawful or unauthorized purposes
    text: Use this website or the Site Materials for any unlawful or unauthorized purpose;
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
name: Hertz
provenance_date: '2026-11-09'
provider_name: Hertz
provider_slug: hertz
slug: hertz-eligibility
source_date: '2026-11-09'
source_filename: hertz-eligibility.yml
source_heading: Eligibility
source_page: https://www.hertz.com/rentacar/navigation/templates/legalView.jsp
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hertz\naid: hertz\nurl: https://www.hertz.com/rentacar/navigation/templates/legalView.jsp\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age to use this website.\nrestricted_uses:\n- summary: Unlawful or unauthorized purposes\n  text: Use this website or the Site Materials for any unlawful or unauthorized purpose;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to use this website.\n"
source_yaml_url: https://artifacts.apis.io/hertz/eligibility/hertz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Hertz's own page on 2026-11-09.
synthetic: false
tags:
- Fortune 500
- Car Rental
- Vehicle Rental
- Travel
- Mobility
- Transportation
- Fleet Management
---
