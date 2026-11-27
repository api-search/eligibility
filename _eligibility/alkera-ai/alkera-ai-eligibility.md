---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: we may restrict access depending on geographic region.
  entity_types:
  - text: If the person accepting this Agreement is doing so on behalf of a company
    type: business
  - text: 'Customer: The company or person who accesses or uses the Product.'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: US export control on models
    text: access to models is subject to US export control
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
name: Alkera Ai
provenance_date: '2026-11-09'
provider_name: Alkera Ai
provider_slug: alkera-ai
slug: alkera-ai-eligibility
source_date: '2026-11-09'
source_filename: alkera-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.alkera.ai/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alkera Ai\naid: alkera-ai\nurl: https://www.alkera.ai/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: we may restrict access depending on geographic region.\nentity_types:\n- type: business\n  text: If the person accepting this Agreement is doing so on behalf of a company\n- type: individual\n  text: 'Customer: The company or person who accesses or uses the Product.'\nrestricted_uses:\n- summary: US export control on models\n  text: access to models is subject to US export control\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alkera-ai/eligibility/alkera-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Alkera Ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Engineering
- AI Agents
- Data Pipeline
- Data Lineage
- Developer Tools
- CLI
- IDE Extension
- Data Stack
---
