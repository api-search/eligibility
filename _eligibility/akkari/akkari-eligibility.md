---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is for businesses, not consumers. By accepting, you represent that you are at least 18, are acting on behalf of a company or other legal entity, and are authorized to bind it.
    type: business
  minimum_age:
    text: you represent that you are at least 18
    value: '18'
  restricted_uses:
  - summary: Life-critical use
    text: use the Service where its failure could cause death, injury, or serious damage
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
name: Akkari
provenance_date: '2026-11-09'
provider_name: Akkari
provider_slug: akkari
slug: akkari-eligibility
source_date: '2026-11-09'
source_filename: akkari-eligibility.yml
source_heading: Eligibility
source_page: https://akkari.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Akkari\naid: akkari\nurl: https://akkari.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is for businesses, not consumers. By accepting, you represent that you are at least 18, are\n    acting on behalf of a company or other legal entity, and are authorized to bind it.\nrestricted_uses:\n- summary: Life-critical use\n  text: use the Service where its failure could cause death, injury, or serious damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: you represent that you are at least 18\n"
source_yaml_url: https://artifacts.apis.io/akkari/eligibility/akkari-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Akkari's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Operations
- Customer Success
- Artificial Intelligence
- Automation
- Workflow Automation
- Software-as-a-Service
- Y Combinator
- AI Agents
---
