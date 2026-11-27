---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE RIGHT, AUTHORITY, AND CAPACITY TO BIND SUCH ENTITY TO THIS AGREEMENT.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use that infringes third-party rights
    text: use the Platform in a manner that violates or infringes any rights of any third party
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
name: Venice
provenance_date: '2026-11-10'
provider_name: Venice
provider_slug: venice
slug: venice-eligibility
source_date: '2026-11-10'
source_filename: venice-eligibility.yml
source_heading: Eligibility
source_page: https://www.venice.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Venice\naid: venice\nurl: https://www.venice.io/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE RIGHT, AUTHORITY,\n    AND CAPACITY TO BIND SUCH ENTITY TO THIS AGREEMENT.\nrestricted_uses:\n- summary: Use that infringes third-party rights\n  text: use the Platform in a manner that violates or infringes any rights of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/venice/eligibility/venice-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Venice's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Privileged Access Management
- Identity Security
- Zero Trust
- Identity and Access Management
- Cybersecurity
---
