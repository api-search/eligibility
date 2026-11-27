---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: individuals residing in the United States may use the Site and/or the Services
  entity_types:
  - text: Our Services are available only to individuals who are eighteen (18) years of age or older.
    type: individual
  - text: You must not be a competitor of THB or using our Services for reasons that are in competition with THB.
    type: business
  minimum_age:
    text: Our Services are available only to individuals who are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Helper accounts for care jobs only
    text: If you are a Helper, you may use your account only to find care jobs for yourself.
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
name: The Helper Bees
provenance_date: '2026-11-10'
provider_name: The Helper Bees
provider_slug: the-helper-bees
slug: the-helper-bees-eligibility
source_date: '2026-11-10'
source_filename: the-helper-bees-eligibility.yml
source_heading: Eligibility
source_page: https://www.thehelperbees.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Helper Bees\naid: the-helper-bees\nurl: https://www.thehelperbees.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: individuals residing in the United States may use the Site and/or the Services\nentity_types:\n- type: individual\n  text: Our Services are available only to individuals who are eighteen (18) years of age or older.\n- type: business\n  text: You must not be a competitor of THB or using our Services for reasons that are in competition with THB.\nrestricted_uses:\n- summary: Helper accounts for care jobs only\n  text: If you are a Helper, you may\
  \ use your account only to find care jobs for yourself.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Services are available only to individuals who are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/the-helper-bees/eligibility/the-helper-bees-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from The Helper Bees's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Aging in Place
- Home Care
- Long-Term Care Insurance
- Medicare Advantage
- Medicaid
- Benefits
- Health Tech
---
