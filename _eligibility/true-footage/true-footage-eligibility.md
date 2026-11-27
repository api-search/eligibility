---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - source: https://www.truefootage.tech/tools/truetracts/terms-of-service
    text: Access to TrueTracts requires an individual, registered account.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harassing, fraudulent, or unlawful material
    text: use this website or its associated services to transmit or publish any harassing, indecent, obscene, fraudulent, or unlawful material;
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
name: True Footage
provenance_date: '2026-11-10'
provider_name: True Footage
provider_slug: true-footage
slug: true-footage-eligibility
source_date: '2026-11-10'
source_filename: true-footage-eligibility.yml
source_heading: Eligibility
source_page: https://www.truefootage.tech/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: True Footage\naid: true-footage\nurl: https://www.truefootage.tech/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.truefootage.tech/terms-of-use\n  - https://www.truefootage.tech/tools/truetracts/terms-of-service\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Access to TrueTracts requires an individual, registered account.\n  source: https://www.truefootage.tech/tools/truetracts/terms-of-service\nrestricted_uses:\n- summary: Harassing, fraudulent, or unlawful material\n  text: use this website or its associated services to transmit or publish\
  \ any harassing, indecent, obscene, fraudulent,\n    or unlawful material;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/true-footage/eligibility/true-footage-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from True Footage's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Appraisal
- Valuation
- PropTech
- Mortgage
- Property Data
- Analytics
- Machine Learning
---
