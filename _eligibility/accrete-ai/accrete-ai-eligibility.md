---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website and Company’s services are primarily intended for users, individuals or entities residing in the United States.
  entity_types:
  - text: By using the Website, you represent and warrant that you are of legal age to form a binding contract with the Company
    type: individual
  minimum_age:
    text: Our Services are not intended for anyone under 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.
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
name: Accrete
provenance_date: '2026-11-09'
provider_name: Accrete
provider_slug: accrete-ai
slug: accrete-ai-eligibility
source_date: '2026-11-09'
source_filename: accrete-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.accrete.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Accrete\naid: accrete-ai\nurl: https://www.accrete.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website and Company’s services are primarily intended for users, individuals or entities residing in\n    the United States.\nentity_types:\n- type: individual\n  text: By using the Website, you represent and warrant that you are of legal age to form a binding contract with\n    the Company\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Services are not intended for anyone under 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/accrete-ai/eligibility/accrete-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Accrete's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Knowledge Graph
- Defense
- Government
- ITSM
- Supply Chain
- Social Media Intelligence
- Enterprise Software
---
