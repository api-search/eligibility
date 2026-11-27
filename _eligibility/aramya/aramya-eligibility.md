---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use of Aramya is available only to individuals who are (i) at least 18 years old and can form legally binding contracts under applicable law, or in the alternative (ii) under 18 years of age, but their legal guardians have agreed to enter into contract on their behalf
    type: individual
  - text: If you use Aramya or open an Account (as defined below) on behalf of a non-individual entity or group, you represent and warrant that you have the authority to bind that entity or group
    type: business
  minimum_age:
    text: at least 18 years old and can form legally binding contracts under applicable law
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To create an account, you must submit your phone number through the account registration page on Aramya and login using OTP authentication.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aramya
provenance_date: '2026-11-09'
provider_name: Aramya
provider_slug: aramya
slug: aramya-eligibility
source_date: '2026-11-09'
source_filename: aramya-eligibility.yml
source_heading: Eligibility
source_page: https://aramya.in/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aramya\naid: aramya\nurl: https://aramya.in/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use of Aramya is available only to individuals who are (i) at least 18 years old and can form legally binding\n    contracts under applicable law, or in the alternative (ii) under 18 years of age, but their legal guardians\n    have agreed to enter into contract on their behalf\n- type: business\n  text: If you use Aramya or open an Account (as defined below) on behalf of a non-individual entity or group, you\n    represent\
  \ and warrant that you have the authority to bind that entity or group\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To create an account, you must submit your phone number through the account registration page on Aramya\n    and login using OTP authentication.\nminimum_age:\n  value: '18'\n  text: at least 18 years old and can form legally binding contracts under applicable law\n"
source_yaml_url: https://artifacts.apis.io/aramya/eligibility/aramya-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Aramya's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Fashion
- E-Commerce
- Retail
- Apparel
- India
- Direct to Consumer
---
