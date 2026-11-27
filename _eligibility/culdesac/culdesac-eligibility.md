---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to submit an inquiry, guest card, or application through the Sites.
    value: '18'
  restricted_uses:
  - summary: Unlawful or fair-housing violating use
    text: use the Sites for any unlawful purpose or in violation of fair-housing laws
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
name: Culdesac
provenance_date: '2026-11-09'
provider_name: Culdesac
provider_slug: culdesac
slug: culdesac-eligibility
source_date: '2026-11-09'
source_filename: culdesac-eligibility.yml
source_heading: Eligibility
source_page: https://culdesac.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Culdesac\naid: culdesac\nurl: https://culdesac.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or fair-housing violating use\n  text: use the Sites for any unlawful purpose or in violation of fair-housing laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to submit an inquiry, guest card, or application through the Sites.\n"
source_yaml_url: https://artifacts.apis.io/culdesac/eligibility/culdesac-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Culdesac's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Real Estate Development
- Housing
- Urban Planning
- Car-Free
- Mobility
- Property Management
---
