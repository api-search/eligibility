---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Services are provided to individuals residing in the United States; Luna does not knowingly collect information from individuals residing outside of the United States.
  minimum_age:
    text: Unless a legal exception applies, in the case of a minor less than 18 years of age, a parent or legal guardian must consent to treatment.
    value: '18'
  restricted_uses:
  - summary: Commercial use prohibited
    text: You will only use the Services for your own internal, personal, non-commercial use
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
name: Luna
provenance_date: '2026-11-10'
provider_name: Luna
provider_slug: luna
slug: luna-eligibility
source_date: '2026-11-10'
source_filename: luna-eligibility.yml
source_heading: Eligibility
source_page: https://www.getluna.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Luna\naid: luna\nurl: https://www.getluna.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Services are provided to individuals residing in the United States; Luna does not knowingly collect information\n    from individuals residing outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: You will only use the Services for your own internal, personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Unless a legal exception\
  \ applies, in the case of a minor less than 18 years of age, a parent or legal guardian\n    must consent to treatment.\n"
source_yaml_url: https://artifacts.apis.io/luna/eligibility/luna-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Luna's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Physical Therapy
- In-Home Care
- Rehabilitation
- Digital Health
---
