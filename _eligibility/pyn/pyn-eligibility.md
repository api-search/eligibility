---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an organization, the individual who agrees to this Agreement on your behalf must have the authority to bind you to this Agreement
    type: business
  minimum_age:
    text: not provide any person under the age of 16 with access to the Services, unless otherwise permitted by applicable law
    value: '16'
  restricted_uses:
  - summary: No use subjecting Pyn to industry-specific regulation
    text: You must not use the Services in a way that would subject Pyn to any industry-specific regulations (for example, the Children’s Online Privacy Protection Act, the Payment Card Industry Data Security Standard or the Health Insurance Portability and Accountability Act).
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
name: Pyn
provenance_date: '2026-11-10'
provider_name: Pyn
provider_slug: pyn
slug: pyn-eligibility
source_date: '2026-11-10'
source_filename: pyn-eligibility.yml
source_heading: Eligibility
source_page: https://www.pynhq.com/info/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pyn\naid: pyn\nurl: https://www.pynhq.com/info/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are an organization, the individual who agrees to this Agreement on your behalf must have the authority\n    to bind you to this Agreement\nrestricted_uses:\n- summary: No use subjecting Pyn to industry-specific regulation\n  text: You must not use the Services in a way that would subject Pyn to any industry-specific regulations (for\n    example, the Children’s Online Privacy Protection Act, the Payment Card Industry\
  \ Data Security Standard or the\n    Health Insurance Portability and Accountability Act).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: not provide any person under the age of 16 with access to the Services, unless otherwise permitted by applicable\n    law\n"
source_yaml_url: https://artifacts.apis.io/pyn/eligibility/pyn-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Pyn's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Human Resources
- Employee Experience
- Employee Onboarding
- Internal Communications
- HR Automation
- Employee Engagement
- Artificial Intelligence
---
