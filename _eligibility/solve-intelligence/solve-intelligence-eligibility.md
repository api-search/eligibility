---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services as an employee, contractor, or agent of a company, corporation, partnership or similar entity, then you must be authorized to sign for and bind the entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive personal data
    text: Customer shall ensure that Customer Data do not contain any of the following categories of sensitive data
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
name: Solve Intelligence
provenance_date: '2026-11-10'
provider_name: Solve Intelligence
provider_slug: solve-intelligence
slug: solve-intelligence-eligibility
source_date: '2026-11-10'
source_filename: solve-intelligence-eligibility.yml
source_heading: Eligibility
source_page: https://www.solveintelligence.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Solve Intelligence\naid: solve-intelligence\nurl: https://www.solveintelligence.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services as an employee, contractor, or agent of a company, corporation, partnership\n    or similar entity, then you must be authorized to sign for and bind the entity\nrestricted_uses:\n- summary: No sensitive personal data\n  text: Customer shall ensure that Customer Data do not contain any of the following categories of sensitive data\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/solve-intelligence/eligibility/solve-intelligence-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Solve Intelligence's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Intellectual Property
- Patents
- Artificial Intelligence
- Document Generation
- Search
- MCP
- Agents
---
