---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Real persons who benefit from the services provided by İnofab by accessing the Website
    type: individual
  minimum_age:
    text: Real person Users acknowledge, represent and undertake that they have attained maturity and are not interdicted in accordance with the relevant legislation. Minors and/or interdicted persons are not entitled to benefit from the rights and powers of being a User
    value: null
  restricted_uses:
  - summary: Illegal or harmful activity
    text: not to engage in any illegal activity while providing access to the Website, benefiting from the services and performing any transaction on the Website.
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
name: Inofab
provenance_date: '2026-11-09'
provider_name: Inofab
provider_slug: inofab
slug: inofab-eligibility
source_date: '2026-11-09'
source_filename: inofab-eligibility.yml
source_heading: Eligibility
source_page: https://www.inofab.health/term-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inofab\naid: inofab\nurl: https://www.inofab.health/term-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Real persons who benefit from the services provided by İnofab by accessing the Website\nrestricted_uses:\n- summary: Illegal or harmful activity\n  text: not to engage in any illegal activity while providing access to the Website, benefiting from the services\n    and performing any transaction on the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: Real person Users acknowledge, represent and undertake that they have attained maturity and are not interdicted\n    in accordance with the relevant legislation. Minors and/or interdicted persons are not entitled to benefit from\n    the rights and powers of being a User\n"
source_yaml_url: https://artifacts.apis.io/inofab/eligibility/inofab-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Inofab's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Health
- Respiratory
- Spirometry
- Medical Devices
- Remote Patient Monitoring
- Connected Devices
- Healthcare
---
