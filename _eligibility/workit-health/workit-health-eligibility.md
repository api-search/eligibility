---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: reside in the United States of America or any of its territories
  entity_types:
  - text: 'Generally, the Service is available only to individuals who: are at least 18 years old; reside in the United States of America or any of its territories'
    type: individual
  minimum_age:
    text: By accessing or using any component of the Service including, but not limited to, creating Login Credentials for accessing the Service, you represent that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: The Service is provided only for your personal, non-commercial, limited use in accordance with these Agreements.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Workit Health reserves the right to authenticate any information you provide.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Workit Health
provenance_date: '2026-11-10'
provider_name: Workit Health
provider_slug: workit-health
slug: workit-health-eligibility
source_date: '2026-11-10'
source_filename: workit-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.workithealth.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Workit Health\naid: workit-health\nurl: https://www.workithealth.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: reside in the United States of America or any of its territories\nentity_types:\n- type: individual\n  text: 'Generally, the Service is available only to individuals who: are at least 18 years old; reside in the United\n    States of America or any of its territories'\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: The Service is provided only for your personal, non-commercial, limited use in accordance\
  \ with these Agreements.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Workit Health reserves the right to authenticate any information you provide.\nminimum_age:\n  value: '18'\n  text: By accessing or using any component of the Service including, but not limited to, creating Login Credentials\n    for accessing the Service, you represent that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/workit-health/eligibility/workit-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Workit Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Healthcare
- Telehealth
- Addiction Treatment
- Behavioral Health
- Digital Health
---
