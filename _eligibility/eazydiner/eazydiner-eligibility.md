---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This company is registered in Gurgaon, Delhi NCR, India.
  entity_types:
  - text: While people under the age of 18 can use the services of EazyDiner, they must do so under the guidance of their parents and/ or legal guardians.
    type: individual
  minimum_age:
    text: While people under the age of 18 can use the services of EazyDiner, they must do so under the guidance of their parents and/ or legal guardians.
    value: '18'
  restricted_uses:
  - summary: Prohibited user content
    text: Users are prohibited from posting or transmitting any defamatory, obscene, pornographic, profane, threatening or unlawful material
  - summary: Alcohol service age
    text: Delhi NCR users booking at bars should be a minimum of 21 years or above.
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
name: Eazydiner
provenance_date: '2026-11-09'
provider_name: Eazydiner
provider_slug: eazydiner
slug: eazydiner-eligibility
source_date: '2026-11-09'
source_filename: eazydiner-eligibility.yml
source_heading: Eligibility
source_page: https://www.eazydiner.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eazydiner\naid: eazydiner\nurl: https://www.eazydiner.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This company is registered in Gurgaon, Delhi NCR, India.\nentity_types:\n- type: individual\n  text: While people under the age of 18 can use the services of EazyDiner, they must do so under the guidance of\n    their parents and/ or legal guardians.\nrestricted_uses:\n- summary: Prohibited user content\n  text: Users are prohibited from posting or transmitting any defamatory, obscene, pornographic, profane, threatening\n    or unlawful material\n- summary:\
  \ Alcohol service age\n  text: Delhi NCR users booking at bars should be a minimum of 21 years or above.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: While people under the age of 18 can use the services of EazyDiner, they must do so under the guidance of\n    their parents and/ or legal guardians.\n"
source_yaml_url: https://artifacts.apis.io/eazydiner/eligibility/eazydiner-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Eazydiner's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Restaurant
- Reservation
- Deals
- India
---
