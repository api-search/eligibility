---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Sanctioned countries/parties
    text: You represent that you are not located in, organized under the laws of, or ordinarily resident in any country or territory subject to comprehensive sanctions, and you are not a denied party under applicable sanctions or export control laws.
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
name: Motley
provenance_date: '2026-11-10'
provider_name: Motley
provider_slug: motley
slug: motley-eligibility
source_date: '2026-11-10'
source_filename: motley-eligibility.yml
source_heading: Eligibility
source_page: https://motley.ai/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Motley\naid: motley\nurl: https://motley.ai/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned countries/parties\n  text: You represent that you are not located in, organized under the laws of, or ordinarily resident in any country\n    or territory subject to comprehensive sanctions, and you are not a denied party under applicable sanctions or\n    export control laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are\
  \ at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/motley/eligibility/motley-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Motley's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Semantic Layer
- Business Intelligence
- Analytics
- AI Agents
- MCP
- SQL
- Data
- Reporting
---
