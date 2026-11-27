---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept these TOS, you represent that you are age 13 or older.
    type: individual
  minimum_age:
    text: If you accept these TOS, you represent that you are age 13 or older. If you are between the ages of 13 and 17 or otherwise do not have the authority to enter into agreements such as these TOS, you represent that your legal guardian, or a holder of parental responsibility, has reviewed and agreed to these TOS.
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: for your personal, non-commercial use
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
name: Playsome
provenance_date: '2026-11-10'
provider_name: Playsome
provider_slug: playsome
slug: playsome-eligibility
source_date: '2026-11-10'
source_filename: playsome-eligibility.yml
source_heading: Eligibility
source_page: https://www.playsome.fi/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Playsome\naid: playsome\nurl: https://www.playsome.fi/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you accept these TOS, you represent that you are age 13 or older.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: for your personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you accept these TOS, you represent that you are age 13 or older. If you are between the ages of 13 and\n    17 or otherwise\
  \ do not have the authority to enter into agreements such as these TOS, you represent that your\n    legal guardian, or a holder of parental responsibility, has reviewed and agreed to these TOS.\n"
source_yaml_url: https://artifacts.apis.io/playsome/eligibility/playsome-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Playsome's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mobile Gaming
- Games
- Game Studio
- Free-to-Play
- Finland
- Consumer
- MCP
---
