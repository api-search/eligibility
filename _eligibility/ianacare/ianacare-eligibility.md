---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site and Service is controlled within the U.S. and is limited to use by citizens of the U.S. who are at least 18 years old.
  entity_types:
  - text: This license is limited to individuals over the age of eighteen who are residents of the United States of America (“U.S.”).
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical, legal or professional advice
    text: IANACARE DOES NOT DISPENSE MEDICAL, DIAGNOSIS, TREATMENT ADVICE, OR THE ADVICE OF ANY LICENSED HEALTHCARE PROFESSIONAL.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to each Individual Site is by invitation only.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ianacare
provenance_date: '2026-11-09'
provider_name: ianacare
provider_slug: ianacare
slug: ianacare-eligibility
source_date: '2026-11-09'
source_filename: ianacare-eligibility.yml
source_heading: Eligibility
source_page: https://ianacare.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ianacare\naid: ianacare\nurl: https://ianacare.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site and Service is controlled within the U.S. and is limited to use by citizens of the U.S. who are\n    at least 18 years old.\nentity_types:\n- type: individual\n  text: This license is limited to individuals over the age of eighteen who are residents of the United States of\n    America (“U.S.”).\nrestricted_uses:\n- summary: No medical, legal or professional advice\n  text: IANACARE DOES NOT DISPENSE MEDICAL, DIAGNOSIS, TREATMENT ADVICE, OR THE ADVICE OF\
  \ ANY LICENSED HEALTHCARE\n    PROFESSIONAL.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to each Individual Site is by invitation only.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ianacare/eligibility/ianacare-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from ianacare's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Caregiving
- Employee Benefits
- Digital Health
- Care Navigation
- Health Plans
- Mobile App
- Identity
---
