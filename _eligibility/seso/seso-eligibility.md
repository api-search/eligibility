---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you enter into this Agreement on behalf of a legal entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal, fraudulent or inappropriate use
    text: Customer may not use the Services for illegal, fraudulent, unethical or inappropriate purposes
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
name: Seso
provenance_date: '2026-11-10'
provider_name: Seso
provider_slug: seso
slug: seso-eligibility
source_date: '2026-11-10'
source_filename: seso-eligibility.yml
source_heading: Eligibility
source_page: https://www.sesolabor.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Seso\naid: seso\nurl: https://www.sesolabor.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you enter into this Agreement on behalf of a legal entity\nrestricted_uses:\n- summary: No illegal, fraudulent or inappropriate use\n  text: Customer may not use the Services for illegal, fraudulent, unethical or inappropriate purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/seso/eligibility/seso-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Seso's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Human Resources
- Agriculture
- Payroll
- Onboarding
- H-2A Visa
- Compliance
- Workforce Management
---
