---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services may not be available in all countries.
  entity_types:
  - text: You must be 18 years of age, or the age of majority in your province, territory or country, whichever is greater, to become a subscriber to the Services. Minors that are at least 13 years of age may only use the Services under the supervision of an adult.
    type: individual
  minimum_age:
    text: You must be 18 years of age, or the age of majority in your province, territory or country, whichever is greater, to become a subscriber to the Services.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use
    text: The Services and any content viewed through the Services are for your personal and non-commercial use only
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
name: MUBI
provenance_date: '2026-11-10'
provider_name: MUBI
provider_slug: mubi
slug: mubi-eligibility
source_date: '2026-11-10'
source_filename: mubi-eligibility.yml
source_heading: Eligibility
source_page: https://mubi.com/en/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MUBI\naid: mubi\nurl: https://mubi.com/en/terms_of_service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services may not be available in all countries.\nentity_types:\n- type: individual\n  text: You must be 18 years of age, or the age of majority in your province, territory or country, whichever is\n    greater, to become a subscriber to the Services. Minors that are at least 13 years of age may only use the Services\n    under the supervision of an adult.\nrestricted_uses:\n- summary: Personal non-commercial use\n  text: The Services and any content viewed through the Services\
  \ are for your personal and non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age, or the age of majority in your province, territory or country, whichever is\n    greater, to become a subscriber to the Services.\n"
source_yaml_url: https://artifacts.apis.io/mubi/eligibility/mubi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from MUBI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Streaming
- Media
- Entertainment
- Film
- Video-on-Demand
- Subscription
- Distribution
---
