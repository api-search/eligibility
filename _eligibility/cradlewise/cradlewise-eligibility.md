---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - AU
    - IN
    text: Currently, our Platform is being offered to residents of the United States, Canada, Australia and India only.
  entity_types:
  - text: You represent and warrant that you are at least 18 years of age.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No medical advice
    text: THE SERVICES DO NOT PROVIDE MEDICAL ADVICE AND ARE INTENDED FOR YOUR PERSONAL INFORMATIONAL USE ONLY.
  - summary: Services not for third-party benefit
    text: The Services are offered only for Users and children associated with Users’ accounts, and not for the use or benefit of any third party, except as explicitly authorized by Cradlewise through approved third-party integrations, developer tools, or application programming interfaces (APIs).
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
name: Cradlewise
provenance_date: '2026-11-09'
provider_name: Cradlewise
provider_slug: cradlewise
slug: cradlewise-eligibility
source_date: '2026-11-09'
source_filename: cradlewise-eligibility.yml
source_heading: Eligibility
source_page: https://cradlewise.com/en-US/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cradlewise\naid: cradlewise\nurl: https://cradlewise.com/en-US/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  - AU\n  - IN\n  excluded: []\n  text: Currently, our Platform is being offered to residents of the United States, Canada, Australia and India\n    only.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years of age.\nrestricted_uses:\n- summary: No medical advice\n  text: THE SERVICES DO NOT PROVIDE MEDICAL ADVICE AND ARE INTENDED FOR YOUR PERSONAL INFORMATIONAL USE ONLY.\n- summary: Services not for third-party\
  \ benefit\n  text: The Services are offered only for Users and children associated with Users’ accounts, and not for the use\n    or benefit of any third party, except as explicitly authorized by Cradlewise through approved third-party integrations,\n    developer tools, or application programming interfaces (APIs).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/cradlewise/eligibility/cradlewise-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cradlewise's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Baby
- Smart Home
- IoT
- Parenting
---
