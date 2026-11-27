---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If your country of residence is in the United States, our group company Travelscape, LLC will collect your payment on behalf of Tiqets International B.V.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-personal or resale use
    text: Our platform is built for personal use, which means that we, for example, do not like if you would purchase tickets via us for reselling to others.
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
name: Tiqets
provenance_date: '2026-11-10'
provider_name: Tiqets
provider_slug: tiqets
slug: tiqets-eligibility
source_date: '2026-11-10'
source_filename: tiqets-eligibility.yml
source_heading: Eligibility
source_page: https://www.tiqets.com/en/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tiqets\naid: tiqets\nurl: https://www.tiqets.com/en/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If your country of residence is in the United States, our group company Travelscape, LLC will collect your\n    payment on behalf of Tiqets International B.V.\nentity_types: []\nrestricted_uses:\n- summary: Non-personal or resale use\n  text: Our platform is built for personal use, which means that we, for example, do not like if you would purchase\n    tickets via us for reselling to others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tiqets/eligibility/tiqets-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Tiqets's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Ticketing
- Marketplace
---
