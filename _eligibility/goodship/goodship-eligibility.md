---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Use of our Services is currently authorized only in the United States.
  entity_types:
  - text: Our Services are provided for your internal business use and not for the benefit or use of any third party.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: you may not remove or export from the United States or allow the export or re-export of the Services, Software or anything related thereto
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
name: GoodShip
provenance_date: '2026-11-09'
provider_name: GoodShip
provider_slug: goodship
slug: goodship-eligibility
source_date: '2026-11-09'
source_filename: goodship-eligibility.yml
source_heading: Eligibility
source_page: https://www.goodship.io/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GoodShip\naid: goodship\nurl: https://www.goodship.io/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Use of our Services is currently authorized only in the United States.\nentity_types:\n- type: business\n  text: Our Services are provided for your internal business use and not for the benefit or use of any third party.\nrestricted_uses:\n- summary: Export restrictions\n  text: you may not remove or export from the United States or allow the export or re-export of the Services, Software\n    or anything related thereto\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/goodship/eligibility/goodship-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from GoodShip's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Freight
- Logistics
- Transportation
- Procurement
- Supply Chain
- Analytics
- Artificial Intelligence
---
