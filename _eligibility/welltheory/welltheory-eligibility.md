---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you choose to access the Services from or use the Services outside the United States, you do so on your own initiative and you are solely responsible for complying with applicable local laws in your country.
  entity_types:
  - text: We grant to you, for your personal purposes as an individual consumer only
    type: individual
  minimum_age:
    text: You must be at least 18 years old to register and use the Service.
    value: '18'
  restricted_uses:
  - summary: No commercial use or resale
    text: (d) market, sell or resell the Service to any third party or otherwise commercially use the Service
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: WellTheory and its team of licensed clinicians has the right to accept or reject any applicant for Services, in its sole and complete discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: WellTheory
provenance_date: '2026-11-10'
provider_name: WellTheory
provider_slug: welltheory
slug: welltheory-eligibility
source_date: '2026-11-10'
source_filename: welltheory-eligibility.yml
source_heading: Eligibility
source_page: https://www.welltheory.com/terms/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WellTheory\naid: welltheory\nurl: https://www.welltheory.com/terms/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: If you choose to access the Services from or use the Services outside the United States, you do so on your\n    own initiative and you are solely responsible for complying with applicable local laws in your country.\nentity_types:\n- type: individual\n  text: We grant to you, for your personal purposes as an individual consumer only\nrestricted_uses:\n- summary: No commercial use or resale\n  text: (d) market, sell or resell the\
  \ Service to any third party or otherwise commercially use the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: WellTheory and its team of licensed clinicians has the right to accept or reject any applicant for Services,\n    in its sole and complete discretion.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register and use the Service.\n"
source_yaml_url: https://artifacts.apis.io/welltheory/eligibility/welltheory-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from WellTheory's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Healthcare
- Autoimmune
- Telehealth
- Digital Health
- Employee Benefits
---
