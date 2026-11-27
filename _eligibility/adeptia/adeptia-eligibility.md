---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - KP
    - IR
    - SY
    - SD
    served: []
    text: Such countries currently include at least Cuba, North Korea, Iran, Syria and Sudan; Adeptia, Inc. may not provide services to residents of these countries.
  entity_types:
  - text: In order to use this website, you must be an individual at least 18 years of age, or, if between 13 and 18 years of age, have consent from your parent or guardian.
    type: individual
  minimum_age:
    text: you must be an individual at least 18 years of age, or, if between 13 and 18 years of age, have consent from your parent or guardian.
    value: '18'
  restricted_uses:
  - summary: No automated or unconventional access
    text: You specifically agree not to access (or attempt to access) any of our Resources through any automated, unethical or unconventional means
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- KP
- IR
- SY
- SD
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Adeptia
provenance_date: '2026-11-09'
provider_name: Adeptia
provider_slug: adeptia
slug: adeptia-eligibility
source_date: '2026-11-09'
source_filename: adeptia-eligibility.yml
source_heading: Eligibility
source_page: https://www.adeptia.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adeptia\naid: adeptia\nurl: https://www.adeptia.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - KP\n  - IR\n  - SY\n  - SD\n  text: Such countries currently include at least Cuba, North Korea, Iran, Syria and Sudan; Adeptia, Inc. may not\n    provide services to residents of these countries.\nentity_types:\n- type: individual\n  text: In order to use this website, you must be an individual at least 18 years of age, or, if between 13 and\n    18 years of age, have consent from your parent or guardian.\nrestricted_uses:\n- summary: No automated or unconventional\
  \ access\n  text: You specifically agree not to access (or attempt to access) any of our Resources through any automated,\n    unethical or unconventional means\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be an individual at least 18 years of age, or, if between 13 and 18 years of age, have consent\n    from your parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/adeptia/eligibility/adeptia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Adeptia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Integration
- ETL
- Automation
- Artificial Intelligence
---
