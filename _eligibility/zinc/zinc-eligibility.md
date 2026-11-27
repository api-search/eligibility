---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The counterparty (“You”, “Your”, “Yours” or “Company”) on behalf of itself and any affiliates, whose registered country, address and signature are set out in the Order Form.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful material
    text: 'You shall not access, store, distribute or transmit any material that: is unlawful, harmful, threatening, defamatory, obscene, infringing, harassing or racially or ethnically offensive; or facilitates illegal activity.'
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
name: Zinc
provenance_date: '2026-11-10'
provider_name: Zinc
provider_slug: zinc
slug: zinc-eligibility
source_date: '2026-11-10'
source_filename: zinc-eligibility.yml
source_heading: Eligibility
source_page: https://zincwork.com/legal/committed-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zinc\naid: zinc\nurl: https://zincwork.com/legal/committed-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The counterparty (“You”, “Your”, “Yours” or “Company”) on behalf of itself and any affiliates, whose registered\n    country, address and signature are set out in the Order Form.\nrestricted_uses:\n- summary: Unlawful or harmful material\n  text: 'You shall not access, store, distribute or transmit any material that: is unlawful, harmful, threatening,\n    defamatory, obscene, infringing, harassing or racially\
  \ or ethnically offensive; or facilitates illegal activity.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zinc/eligibility/zinc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Zinc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Background Checks
- Employment Screening
- Identity Verification
- Human Resources
- Recruiting
- Compliance
---
