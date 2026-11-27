---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you are a legal resident of the United States.
  entity_types:
  - text: You must be at least eighteen (18) years old to use the Services.
    type: individual
  - text: A business cannot register for the Atlas Services.
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Personal and non-commercial use only
    text: You will only use the Services for your own personal and non-commercial use
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You hereby authorize Atlas, directly or through third parties, to make any inquiries we consider necessary to validate your identity and/or authenticate your identity and account information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Atlas Card
provenance_date: '2026-11-09'
provider_name: Atlas Card
provider_slug: atlascard
slug: atlascard-eligibility
source_date: '2026-11-09'
source_filename: atlascard-eligibility.yml
source_heading: Eligibility
source_page: https://atlascard.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atlas Card\naid: atlascard\nurl: https://atlascard.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you are a legal resident of the United States.\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to use the Services.\n- type: business\n  text: A business cannot register for the Atlas Services.\nrestricted_uses:\n- summary: Personal and non-commercial use only\n  text: You will only use the Services for your own personal and non-commercial use\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You\
  \ hereby authorize Atlas, directly or through third parties, to make any inquiries we consider necessary\n    to validate your identity and/or authenticate your identity and account information.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/atlascard/eligibility/atlascard-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Atlas Card's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- Credit Cards
- Charge Card
- Payments
- Rewards
- Concierge
- Luxury
- Consumer Finance
---
