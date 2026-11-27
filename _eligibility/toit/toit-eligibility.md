---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the legal entity set out in the order form which is not Us ("You" or "Your") has purchased and governs how You may access and make use of the Toit Platform.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unauthorized access or denial-of-service attacks
    text: You must not attempt to gain unauthorised access to the Toit Platform, the server on which the Online Platform is stored or any server, computer or database connected to the Toit Platform.
  - summary: GDPR personal data only under a DPA
    text: You may use the Toit Platform in connection with personal data subject to the EU General Data Protection Regulation (the “GDPR”) only if You first enter into the Toit Data Processing Agreement (the “Toit DPA”)
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
name: Toit
provenance_date: '2026-11-10'
provider_name: Toit
provider_slug: toit
slug: toit-eligibility
source_date: '2026-11-10'
source_filename: toit-eligibility.yml
source_heading: Eligibility
source_page: https://toit.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Toit\naid: toit\nurl: https://toit.io/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the legal entity set out in the order form which is not Us (\"You\" or \"Your\") has purchased and governs how\n    You may access and make use of the Toit Platform.\nrestricted_uses:\n- summary: No unauthorized access or denial-of-service attacks\n  text: You must not attempt to gain unauthorised access to the Toit Platform, the server on which the Online Platform\n    is stored or any server, computer or database connected to the\
  \ Toit Platform.\n- summary: GDPR personal data only under a DPA\n  text: You may use the Toit Platform in connection with personal data subject to the EU General Data Protection\n    Regulation (the “GDPR”) only if You first enter into the Toit Data Processing Agreement (the “Toit DPA”)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/toit/eligibility/toit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Toit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- IoT
- Embedded
- ESP32
- Microcontrollers
- Programming Language
- Fleet Management
- Firmware
- Developer Tools
- gRPC
---
