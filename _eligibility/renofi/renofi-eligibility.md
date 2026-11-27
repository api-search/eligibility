---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are intended for use in the United States only.
  entity_types:
  - text: To use any Services that require a login account or registration, you must be at least eighteen (18) years old or the age of majority in your state and able to enter into legal contracts
    type: individual
  minimum_age:
    text: Our Services are not designed for anyone under the age of 18 or the age of majority in your state to enter into legal contracts.
    value: '18'
  restricted_uses:
  - summary: Prohibited uses list
    text: 'you agree to not use the Services to: (a) email or otherwise upload any content that (i) infringes any intellectual property'
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
name: RenoFi
provenance_date: '2026-11-10'
provider_name: RenoFi
provider_slug: renofi
slug: renofi-eligibility
source_date: '2026-11-10'
source_filename: renofi-eligibility.yml
source_heading: Eligibility
source_page: https://www.renofi.com/notices/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RenoFi\naid: renofi\nurl: https://www.renofi.com/notices/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are intended for use in the United States only.\nentity_types:\n- type: individual\n  text: To use any Services that require a login account or registration, you must be at least eighteen (18) years\n    old or the age of majority in your state and able to enter into legal contracts\nrestricted_uses:\n- summary: Prohibited uses list\n  text: 'you agree to not use the Services to: (a) email or otherwise upload any content that (i) infringes any\n    intellectual\
  \ property'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Services are not designed for anyone under the age of 18 or the age of majority in your state to enter\n    into legal contracts.\n"
source_yaml_url: https://artifacts.apis.io/renofi/eligibility/renofi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from RenoFi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Home Improvement
- Real Estate
- Mortgage
- Home Equity
- Renovation Financing
---
