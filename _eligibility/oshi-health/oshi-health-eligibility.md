---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Site and/or the Services is limited exclusively to users located in States within the United States where the Services are available. Services are not available to users located outside the United States.
  entity_types:
  - text: license to use Site and Services solely for your personal and non-commercial use.
    type: individual
  minimum_age:
    text: The Site and Services are only for users older than the age of 13.
    value: '13'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: solely for your personal and non-commercial use
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
name: Oshi Health
provenance_date: '2026-11-10'
provider_name: Oshi Health
provider_slug: oshi-health
slug: oshi-health-eligibility
source_date: '2026-11-10'
source_filename: oshi-health-eligibility.yml
source_heading: Eligibility
source_page: https://oshihealth.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oshi Health\naid: oshi-health\nurl: https://oshihealth.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Site and/or the Services is limited exclusively to users located in States within\n    the United States where the Services are available. Services are not available to users located outside the\n    United States.\nentity_types:\n- type: individual\n  text: license to use Site and Services solely for your personal and non-commercial use.\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: solely for your personal\
  \ and non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site and Services are only for users older than the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/oshi-health/eligibility/oshi-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Oshi Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Gastroenterology
- Digital Health
- Virtual Care
---
