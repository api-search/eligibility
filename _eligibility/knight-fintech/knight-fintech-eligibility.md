---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In case of persons other than individuals, an entity holding an account and accessing the Platform through authorised representatives.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or fraudulent activity
    text: Clients shall not use the Platform for fraudulent or unlawful activities.
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
name: Knight Fintech
provenance_date: '2026-11-09'
provider_name: Knight Fintech
provider_slug: knight-fintech
slug: knight-fintech-eligibility
source_date: '2026-11-09'
source_filename: knight-fintech-eligibility.yml
source_heading: Eligibility
source_page: https://knightfintech.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Knight Fintech\naid: knight-fintech\nurl: https://knightfintech.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: In case of persons other than individuals, an entity holding an account and accessing the Platform through\n    authorised representatives.\nrestricted_uses:\n- summary: Illegal or fraudulent activity\n  text: Clients shall not use the Platform for fraudulent or unlawful activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/knight-fintech/eligibility/knight-fintech-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Knight Fintech's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Financial Services
- Banking
- Lending
- Fintech
- Treasury Management
- Embedded Finance
- Supply Chain Finance
- India
---
