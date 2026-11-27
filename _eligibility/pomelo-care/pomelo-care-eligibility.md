---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are controlled by Pomelo Care, which is located in the United States of America. We make no representation that the Services or Content are appropriate or available for use in locations outside of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: You may use the Services only for lawful purposes and in accordance with these Terms.
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
name: Pomelo Care
provenance_date: '2026-11-10'
provider_name: Pomelo Care
provider_slug: pomelo-care
slug: pomelo-care-eligibility
source_date: '2026-11-10'
source_filename: pomelo-care-eligibility.yml
source_heading: Eligibility
source_page: https://www.pomelocare.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pomelo Care\naid: pomelo-care\nurl: https://www.pomelocare.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are controlled by Pomelo Care, which is located in the United States of America. We make no\n    representation that the Services or Content are appropriate or available for use in locations outside of the\n    United States.\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: You may use the Services only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pomelo-care/eligibility/pomelo-care-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Pomelo Care's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Maternity
- Pediatrics
- Women's Health
- Virtual Care
- Value-Based Care
- Digital Health
---
