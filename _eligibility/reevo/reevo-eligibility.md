---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting this Agreement on behalf of Customer, you represent and warrant that you have the authority to bind Customer to the terms and conditions of this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Bulk data transfer restrictions
    text: Customer shall not transfer Covered Data to any Country of Concern or Covered Person or otherwise process Covered Data in a way that would constitute a Restricted Transaction or Prohibited Transaction if done by a U.S. Person.
  - summary: Export-controlled technical data
    text: Customer shall not submit to the Services, including through connected email, calendar, meeting, or call sources, any technical data controlled under the International Traffic in Arms Regulations
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
name: Reevo
provenance_date: '2026-11-10'
provider_name: Reevo
provider_slug: reevo
slug: reevo-eligibility
source_date: '2026-11-10'
source_filename: reevo-eligibility.yml
source_heading: Eligibility
source_page: https://reevo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reevo\naid: reevo\nurl: https://reevo.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting this Agreement on behalf of Customer, you represent and warrant that you have the authority\n    to bind Customer to the terms and conditions of this Agreement.\nrestricted_uses:\n- summary: Bulk data transfer restrictions\n  text: Customer shall not transfer Covered Data to any Country of Concern or Covered Person or otherwise process\n    Covered Data in a way that would constitute a Restricted Transaction or Prohibited\
  \ Transaction if done by a\n    U.S. Person.\n- summary: Export-controlled technical data\n  text: Customer shall not submit to the Services, including through connected email, calendar, meeting, or call\n    sources, any technical data controlled under the International Traffic in Arms Regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/reevo/eligibility/reevo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Reevo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Sales
- CRM
- Revenue Operations
- Sales Automation
- Lead Generation
- Agents
- MCP
- Sales Engagement
- A2A
---
