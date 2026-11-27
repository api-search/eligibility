---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Sites are created and controlled by Papaya in the United Kingdom
  entity_types:
  - text: Whether you’re a consumer or a business user
    type: individual
  - text: 'If you’re a business user: We exclude all implied conditions, warranties, representations, or other terms that may apply to the Sites or any content on any of the Sites.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal purposes
    text: You agree not to use the services available at the Sites for illegal purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must provide certain current, complete, and accurate information about you as prompted to do so by our online forms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Papaya
provenance_date: '2026-11-10'
provider_name: Papaya
provider_slug: papayadash-com
slug: papayadash-com-eligibility
source_date: '2026-11-10'
source_filename: papayadash-com-eligibility.yml
source_heading: Eligibility
source_page: https://papayadash.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Papaya\naid: papayadash-com\nurl: https://papayadash.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Sites are created and controlled by Papaya in the United Kingdom\nentity_types:\n- type: individual\n  text: Whether you’re a consumer or a business user\n- type: business\n  text: 'If you’re a business user: We exclude all implied conditions, warranties, representations, or other terms\n    that may apply to the Sites or any content on any of the Sites.'\nrestricted_uses:\n- summary: Illegal purposes\n  text: You agree not to use the services available\
  \ at the Sites for illegal purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must provide certain current, complete, and accurate information about you as prompted to do so by our\n    online forms.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/papayadash-com/eligibility/papayadash-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Papaya's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Fleet Management
- Logistics
- Software-as-a-Service
- Transportation
---
