---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you employ less than 100 people or have annual turnover of less than $10 million, these terms apply to you
    type: business
  - text: If, at the time of purchasing our services, your business employs more than 100 people or has an annual turnover of $10 million or more, and you are acquiring the services for your own use, these terms apply to you.
    type: business
  - text: If you are wholesaling or reselling our services (or incorporating our services into your own network) to service your customers.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Vocus
provenance_date: '2026-11-10'
provider_name: Vocus
provider_slug: vocus
slug: vocus-eligibility
source_date: '2026-11-10'
source_filename: vocus-eligibility.yml
source_heading: Eligibility
source_page: https://www.vocus.com.au/help-and-support/legal-contracts
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vocus\naid: vocus\nurl: https://www.vocus.com.au/help-and-support/legal-contracts\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you employ less than 100 people or have annual turnover of less than $10 million, these terms apply to\n    you\n- type: business\n  text: If, at the time of purchasing our services, your business employs more than 100 people or has an annual\n    turnover of $10 million or more, and you are acquiring the services for your own use, these terms apply to you.\n- type: business\n  text: If you are wholesaling\
  \ or reselling our services (or incorporating our services into your own network) to\n    service your customers.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vocus/eligibility/vocus-eligibility.yml
stated_fields:
- entity_types
summary_line: 3 quoted statements, read from Vocus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Telecommunications
- Fibre
- Networking
- Wholesale
- Internet Service Provider
- Australia
---
