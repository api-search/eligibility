---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This agreement is between Mapped and you or your company
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Customer may be required by Mapped to successfully pass Mapped’s compliance reviews, which may include automated verifications, online questionnaires, and requests for information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mapped
provenance_date: '2026-11-10'
provider_name: Mapped
provider_slug: mapped-com
slug: mapped-com-eligibility
source_date: '2026-11-10'
source_filename: mapped-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.mapped.com/legal/CustomerAgreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mapped\naid: mapped-com\nurl: https://www.mapped.com/legal/CustomerAgreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This agreement is between Mapped and you or your company\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Customer may be required by Mapped to successfully pass Mapped’s compliance reviews, which may include automated\n    verifications, online questionnaires, and requests for information\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mapped-com/eligibility/mapped-com-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Mapped's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Smart Buildings
- IoT
- GraphQL
- Data Integration
- Ontology
- Physical AI
- MCP
---
