---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: No countries are named as served or excluded. Section 12.2 requires export compliance for use 'outside Sweden or the EU' but lists no excluded country.
  entity_types:
  - text: If the individual accepting this Agreement is accepting on behalf of a company or other legal entity, such individual represents that they have the authority to bind such entity
    type: business
  minimum_age:
    text: The Services are not intended for and should not be used by anyone under the age of sixteen (16).
    value: '16'
  restricted_uses:
  - summary: Life-critical or safety uses
    text: use the Services for any activity where use or failure of the Services could lead to death, personal injury, or environmental damage, including life support systems, emergency services, nuclear facilities, autonomous vehicles, or air traffic control.
  - summary: Sensitive data
    text: Customer will not use the Services to store or otherwise process Sensitive Data
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
name: Stilla
provenance_date: '2026-11-10'
provider_name: Stilla
provider_slug: stilla
slug: stilla-eligibility
source_date: '2026-11-10'
source_filename: stilla-eligibility.yml
source_heading: Eligibility
source_page: https://stilla.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stilla\naid: stilla\nurl: https://stilla.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: No countries are named as served or excluded. Section 12.2 requires export compliance for use 'outside Sweden\n    or the EU' but lists no excluded country.\nentity_types:\n- type: business\n  text: If the individual accepting this Agreement is accepting on behalf of a company or other legal entity, such\n    individual represents that they have the authority to bind such entity\nrestricted_uses:\n- summary: Life-critical or safety uses\n  text: use the Services for\
  \ any activity where use or failure of the Services could lead to death, personal injury,\n    or environmental damage, including life support systems, emergency services, nuclear facilities, autonomous\n    vehicles, or air traffic control.\n- summary: Sensitive data\n  text: Customer will not use the Services to store or otherwise process Sensitive Data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Services are not intended for and should not be used by anyone under the age of sixteen (16).\n"
source_yaml_url: https://artifacts.apis.io/stilla/eligibility/stilla-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Stilla's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Productivity
- Collaboration
- MCP
- Automation
- Developer Tools
- Enterprise
---
