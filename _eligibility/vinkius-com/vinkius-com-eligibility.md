---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of an organization or legal entity, you represent and warrant that you have the authority to bind such entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 16 years of age (or the applicable age of digital consent in your jurisdiction) to use the Service.
    value: '16'
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
name: Vinkius
provenance_date: '2026-11-10'
provider_name: Vinkius
provider_slug: vinkius-com
slug: vinkius-com-eligibility
source_date: '2026-11-10'
source_filename: vinkius-com-eligibility.yml
source_heading: Eligibility
source_page: https://vinkius.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vinkius\naid: vinkius-com\nurl: https://vinkius.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of an organization or legal entity, you represent and\n    warrant that you have the authority to bind such entity to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age (or the applicable age of digital consent in your jurisdiction)\
  \ to\n    use the Service.\n"
source_yaml_url: https://artifacts.apis.io/vinkius-com/eligibility/vinkius-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Vinkius's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- AI Agents
- Integration
- Connectors
- AI Governance
- Developer Tools
- Agent-Native
---
