---
claim_count: 2
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: End User is not accessing or using Company's products... from any of the jurisdictions against which the United States maintains comprehensive sanctions, which jurisdictions currently include Cuba, Iran, North Korea, Syria, the Crimea region of Ukraine, and the so-called Donetsk People's Republic and Luhansk People's Republic regions (in Ukraine)
  entity_types:
  - text: If you are accessing or using the Services on behalf of your company or another legal entity, you represent that you are authorized to accept this Agreement on behalf of your company
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SAFE Security
provenance_date: '2026-11-10'
provider_name: SAFE Security
provider_slug: safe-security
slug: safe-security-eligibility
source_date: '2026-11-10'
source_filename: safe-security-eligibility.yml
source_heading: Eligibility
source_page: https://safe.security/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SAFE Security\naid: safe-security\nurl: https://safe.security/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: End User is not accessing or using Company's products... from any of the jurisdictions against which the\n    United States maintains comprehensive sanctions, which jurisdictions currently include Cuba, Iran, North Korea,\n    Syria, the Crimea region of Ukraine, and the so-called Donetsk People's Republic and Luhansk People's Republic\n    regions (in Ukraine)\nentity_types:\n- type: business\n  text: If you are accessing or\
  \ using the Services on behalf of your company or another legal entity, you represent\n    that you are authorized to accept this Agreement on behalf of your company\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/safe-security/eligibility/safe-security-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from SAFE Security's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Cyber Risk Quantification
- Third-Party Risk Management
- Continuous Threat Exposure Management
- AI Security Posture Management
- Risk Management
- Governance Risk and Compliance
- FAIR
- Vulnerability Management
---
