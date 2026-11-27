---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that the Information is appropriate or available for use in any particular location worldwide. You may not use the Site in any place where such access is prohibited.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Site only for lawful purposes and in accordance with these Terms of Use.
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
name: RapidRatings
provenance_date: '2026-11-10'
provider_name: RapidRatings
provider_slug: rapidratings
slug: rapidratings-eligibility
source_date: '2026-11-10'
source_filename: rapidratings-eligibility.yml
source_heading: Eligibility
source_page: https://www.rapidratings.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RapidRatings\naid: rapidratings\nurl: https://www.rapidratings.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that the Information is appropriate or available for use in any particular location\n    worldwide. You may not use the Site in any place where such access is prohibited.\nentity_types: []\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Site only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rapidratings/eligibility/rapidratings-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from RapidRatings's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Risk Management
- Supply Chain
- Credit
- Third Party
---
