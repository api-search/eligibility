---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You are in the 50 United States, the District of Columbia, or the US territory of Puerto Rico.
  entity_types:
  - text: You are an individual who is eighteen (18) years of age or older.
    type: individual
  - text: Your employer or insurance provider offers Hello Heart’s Service as part of your health benefits.
    type: other
  minimum_age:
    text: You are an individual who is eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: The Application is not for use by healthcare providers or for any other commercial or non-personal purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To create an account, you must provide us with your name, e-mail address, employer enrollment code, and other data as prompted by the registration process
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hello Heart
provenance_date: '2026-11-09'
provider_name: Hello Heart
provider_slug: hello-heart
slug: hello-heart-eligibility
source_date: '2026-11-09'
source_filename: hello-heart-eligibility.yml
source_heading: Eligibility
source_page: https://www.helloheart.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hello Heart\naid: hello-heart\nurl: https://www.helloheart.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You are in the 50 United States, the District of Columbia, or the US territory of Puerto Rico.\nentity_types:\n- type: individual\n  text: You are an individual who is eighteen (18) years of age or older.\n- type: other\n  text: Your employer or insurance provider offers Hello Heart’s Service as part of your health benefits.\nrestricted_uses:\n- summary: Personal use only\n  text: The Application is not for use by healthcare providers or for any other commercial\
  \ or non-personal purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To create an account, you must provide us with your name, e-mail address, employer enrollment code, and\n    other data as prompted by the registration process\nminimum_age:\n  value: '18'\n  text: You are an individual who is eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/hello-heart/eligibility/hello-heart-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Hello Heart's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Cardiovascular
- Blood Pressure
- Hypertension
- Remote Patient Monitoring
- Health AI
- Employer Benefits
---
