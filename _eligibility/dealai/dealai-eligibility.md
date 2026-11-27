---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If an individual is agreeing to these Terms on behalf of an entity, organization, or company (an " Organization "), (a) the individual accepting these Terms on behalf of the Organization represents and warrants that they have authority to bind the Organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal or highly regulated goods
    text: facilitate or promote the exchange of illegal or highly regulated goods
  - summary: High-risk contexts without review
    text: use Output without appropriate review in high-risk or sensitive contexts, such as in the fields of medicine, law, finance, physical security, or critical infrastructure
  - summary: Political manipulation or misinformation
    text: use the Services or any Output to engage in political activity, including any manipulation or attempted manipulation of governments or elections
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
name: Deal.ai
provenance_date: '2026-11-09'
provider_name: Deal.ai
provider_slug: dealai
slug: dealai-eligibility
source_date: '2026-11-09'
source_filename: dealai-eligibility.yml
source_heading: Eligibility
source_page: https://home.deal.ai/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deal.ai\naid: dealai\nurl: https://home.deal.ai/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If an individual is agreeing to these Terms on behalf of an entity, organization, or company (an \" Organization\n    \"), (a) the individual accepting these Terms on behalf of the Organization represents and warrants that they\n    have authority to bind the Organization to these Terms\nrestricted_uses:\n- summary: Illegal or highly regulated\
  \ goods\n  text: facilitate or promote the exchange of illegal or highly regulated goods\n- summary: High-risk contexts without review\n  text: use Output without appropriate review in high-risk or sensitive contexts, such as in the fields of medicine,\n    law, finance, physical security, or critical infrastructure\n- summary: Political manipulation or misinformation\n  text: use the Services or any Output to engage in political activity, including any manipulation or attempted\n    manipulation of governments or elections\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/dealai/eligibility/dealai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Deal.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Marketing
- Content
- Software-as-a-Service
- Platform
---
