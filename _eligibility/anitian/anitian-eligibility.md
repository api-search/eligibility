---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Subscriber shall not permit Authorized Users to access or use any Products in a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan, Syria or Crimea)
  entity_types:
  - text: If the person is entering into this EULA on behalf of another legal entity, you represent that you have the authority to bind such entity and its affiliates to these terms and conditions
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and embargo restrictions
    text: Subscriber agrees not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired from Anitian, or any products utilizing such data, in violation of the United States export laws or regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Anitian
provenance_date: '2026-11-09'
provider_name: Anitian
provider_slug: anitian
slug: anitian-eligibility
source_date: '2026-11-09'
source_filename: anitian-eligibility.yml
source_heading: Eligibility
source_page: https://www.anitian.com/marketplace-eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anitian\naid: anitian\nurl: https://www.anitian.com/marketplace-eula/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Subscriber shall not permit Authorized Users to access or use any Products in a U.S. embargoed country (currently\n    Cuba, Iran, North Korea, Sudan, Syria or Crimea)\nentity_types:\n- type: business\n  text: If the person is entering into this EULA on behalf of another legal entity, you represent that you have\n    the authority to bind such entity and its affiliates to these terms and conditions\nrestricted_uses:\n- summary:\
  \ Export and embargo restrictions\n  text: Subscriber agrees not to export, reexport, or transfer, directly or indirectly, any U.S. technical data\n    acquired from Anitian, or any products utilizing such data, in violation of the United States export laws or\n    regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anitian/eligibility/anitian-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Anitian's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Compliance
- Cloud
- Governance
- FedRAMP
- Government
- Risk Management
- Audit
- Automation
---
