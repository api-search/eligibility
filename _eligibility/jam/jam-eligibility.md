---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using Jam for a business or organization, the Data Processing Agreement at the end of these Terms may also apply.
    type: business
  minimum_age:
    text: you are old enough to form a binding contract, or you have permission from a parent or guardian who agrees to these Terms on your behalf
    value: null
  restricted_uses:
  - summary: Camera/microphone recording without consent
    text: Do not use the feature to record anyone covertly, and do not use it anywhere recording is prohibited.
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
name: Jam
provenance_date: '2026-11-09'
provider_name: Jam
provider_slug: jam
slug: jam-eligibility
source_date: '2026-11-09'
source_filename: jam-eligibility.yml
source_heading: Eligibility
source_page: https://jam.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jam\naid: jam\nurl: https://jam.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using Jam for a business or organization, the Data Processing Agreement at the end of these Terms\n    may also apply.\nrestricted_uses:\n- summary: Camera/microphone recording without consent\n  text: Do not use the feature to record anyone covertly, and do not use it anywhere recording is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are\
  \ old enough to form a binding contract, or you have permission from a parent or guardian who agrees\n    to these Terms on your behalf\n"
source_yaml_url: https://artifacts.apis.io/jam/eligibility/jam-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Jam's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Bug Reporting
- Debugging
- Quality Assurance
- Observability
- Screen Recording
- MCP
---
