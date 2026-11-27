---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents and warrants that it is not listed on any U.S. government list of prohibited or restricted parties or located in (or a national of) a country that is subject to a U.S. government embargo
  entity_types:
  - text: you or the organization you represent (“Customer” or “You”)
    type: other
  - text: If the user or licensee of the Products is an agency, department, or other entity of the United States Government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-controlled information
    text: will not submit to the Products any information controlled under the U.S. International Traffic in Arms Regulations.
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
name: Sycamore
provenance_date: '2026-11-10'
provider_name: Sycamore
provider_slug: sycamore
slug: sycamore-eligibility
source_date: '2026-11-10'
source_filename: sycamore-eligibility.yml
source_heading: Eligibility
source_page: https://sycamore.so/policies/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sycamore\naid: sycamore\nurl: https://sycamore.so/policies/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents and warrants that it is not listed on any U.S. government list of prohibited or restricted\n    parties or located in (or a national of) a country that is subject to a U.S. government embargo\nentity_types:\n- type: other\n  text: you or the organization you represent (“Customer” or “You”)\n- type: government\n  text: If the user or licensee of the Products is an agency, department, or other entity of the United States Government\n\
  restricted_uses:\n- summary: Export-controlled information\n  text: will not submit to the Products any information controlled under the U.S. International Traffic in Arms\n    Regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sycamore/eligibility/sycamore-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Sycamore's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Agent Operating System
- Enterprise Software
- Agent Governance
- Autonomous Agents
- Enterprise AI
---
