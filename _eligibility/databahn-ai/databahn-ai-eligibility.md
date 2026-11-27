---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are using any service as an employee, contractor, or agent of a corporation, partnership, or similar entity, then You must be authorized to sign for and bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions compliance
    text: Customer affirms that it is not named on, owned by, or acting on behalf of any U.S. government denied-party list
  - summary: Weapons proliferation uses
    text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or biological weapons proliferation
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
name: DataBahn.ai
provenance_date: '2026-11-09'
provider_name: DataBahn.ai
provider_slug: databahn-ai
slug: databahn-ai-eligibility
source_date: '2026-11-09'
source_filename: databahn-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.databahn.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DataBahn.ai\naid: databahn-ai\nurl: https://www.databahn.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are using any service as an employee, contractor, or agent of a corporation, partnership, or similar\n    entity, then You must be authorized to sign for and bind such entity\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: Customer affirms that it is not named on, owned by, or acting on behalf of any U.S. government denied-party\n    list\n- summary: Weapons proliferation uses\n\
  \  text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or\n    biological weapons proliferation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/databahn-ai/eligibility/databahn-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from DataBahn.ai's own page on 2026-11-09.
synthetic: false
tags:
- Data Pipeline
- Security
- Observability
- AI Agents
- Edge Telemetry
- Data Fabric
- SIEM Optimization
- Federated Search
---
