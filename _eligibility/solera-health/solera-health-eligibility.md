---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'Solera’s Products and Services are designed and intended for U.S. citizens who: Live in the U.S.'
  entity_types:
  - text: 'Solera’s Products and Services are designed and intended for U.S. citizens who: Live in the U.S. Are age 18 and older'
    type: individual
  minimum_age:
    text: Are age 18 and older
    value: '18'
  restricted_uses:
  - summary: Unlawful or privacy-violating use
    text: In any way that violates Privacy Laws
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
name: Solera Health
provenance_date: '2026-11-10'
provider_name: Solera Health
provider_slug: solera-health
slug: solera-health-eligibility
source_date: '2026-11-10'
source_filename: solera-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.soleranetwork.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Solera Health\naid: solera-health\nurl: https://www.soleranetwork.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'Solera’s Products and Services are designed and intended for U.S. citizens who: Live in the U.S.'\nentity_types:\n- type: individual\n  text: 'Solera’s Products and Services are designed and intended for U.S. citizens who: Live in the U.S. Are age\n    18 and older'\nrestricted_uses:\n- summary: Unlawful or privacy-violating use\n  text: In any way that violates Privacy Laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n \
  \ text: null\nminimum_age:\n  value: '18'\n  text: Are age 18 and older\n"
source_yaml_url: https://artifacts.apis.io/solera-health/eligibility/solera-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Solera Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Benefits
- Employee Benefits
- Health Plans
- Payers
- Provider Network
- Chronic Condition Management
- Preventive Care
- Telehealth
---
