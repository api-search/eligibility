---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to access or use the Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to access or use the Services.
    value: '18'
  restricted_uses:
  - summary: Downloadable content not for professional advice or commercial use
    text: the Downloadable Content does not constitute legal, financial, investment, tax, accounting, regulatory, compliance, or other similar professional advice and should not be used for any other purpose but your personal, informational, and non-commercial use.
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
name: Ontra AI
provenance_date: '2026-11-10'
provider_name: Ontra AI
provider_slug: ontra-ai
slug: ontra-ai-eligibility
source_date: '2026-11-10'
source_filename: ontra-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.ontra.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ontra AI\naid: ontra-ai\nurl: https://www.ontra.ai/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to access or use the Services.\nrestricted_uses:\n- summary: Downloadable content not for professional advice or commercial use\n  text: the Downloadable Content does not constitute legal, financial, investment, tax, accounting, regulatory,\n    compliance, or other similar professional advice and should not be used for any other purpose but your personal,\n    informational, and non-commercial\
  \ use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to access or use the Services.\n"
source_yaml_url: https://artifacts.apis.io/ontra-ai/eligibility/ontra-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ontra AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal Tech
- Contract Automation
- Private Markets
- Entity Management
- Compliance
- Artificial Intelligence
- MCP
---
