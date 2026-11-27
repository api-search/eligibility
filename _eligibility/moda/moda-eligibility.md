---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if doing so is prohibited in your jurisdiction or if you are barred from receiving them under applicable export control or sanctions laws.
  entity_types:
  - text: The Services are intended for business use by organizations and their authorized personnel.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited jurisdictions
    text: You may not use the Services if doing so is prohibited in your jurisdiction or if you are barred from receiving them under applicable export control or sanctions laws.
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
name: Moda
provenance_date: '2026-11-10'
provider_name: Moda
provider_slug: moda
slug: moda-eligibility
source_date: '2026-11-10'
source_filename: moda-eligibility.yml
source_heading: Eligibility
source_page: https://moda.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moda\naid: moda\nurl: https://moda.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if doing so is prohibited in your jurisdiction or if you are barred from receiving\n    them under applicable export control or sanctions laws.\nentity_types:\n- type: business\n  text: The Services are intended for business use by organizations and their authorized personnel.\nrestricted_uses:\n- summary: Unlawful or prohibited jurisdictions\n  text: You may not use the Services if doing so is prohibited in your jurisdiction or if you are barred from receiving\n\
  \    them under applicable export control or sanctions laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/moda/eligibility/moda-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Moda's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Agents
- LLM Observability
- Agent Analytics
- Continual Learning
- Monitoring
- Developer Tools
- MCP
- OpenTelemetry
- Prompt Management
- Y Combinator
---
