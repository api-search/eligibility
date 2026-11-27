---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or improper purposes
    text: use the Proofpoint API for any illegal, unauthorized, or improper purposes
  - summary: Competitive use
    text: use the Proofpoint API in connection with any product or service or Application that is competitive with Proofpoint’s offerings
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
name: Proofpoint
provenance_date: '2026-11-10'
provider_name: Proofpoint
provider_slug: proofpoint
slug: proofpoint-eligibility
source_date: '2026-11-10'
source_filename: proofpoint-eligibility.yml
source_heading: Eligibility
source_page: https://www.proofpoint.com/us/legal/api-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Proofpoint\naid: proofpoint\nurl: https://www.proofpoint.com/us/legal/api-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or improper purposes\n  text: use the Proofpoint API for any illegal, unauthorized, or improper purposes\n- summary: Competitive use\n  text: use the Proofpoint API in connection with any product or service or Application that is competitive with\n    Proofpoint’s offerings\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/proofpoint/eligibility/proofpoint-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Proofpoint's own page on 2026-11-10.
synthetic: false
tags:
- Security
- Cybersecurity
- Email Security
- Threat Intelligence
- Data Loss Prevention
- Security Awareness Training
- Insider Threat
- SIEM
- Compliance
- Email
---
