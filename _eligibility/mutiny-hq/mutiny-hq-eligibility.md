---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have the legal capacity to form a binding contract.
    type: individual
  - text: IF CUSTOMER IS ACCEPTING ON BEHALF OF AN ENTITY, CUSTOMER REPRESENTS THAT CUSTOMER HAS THE AUTHORITY TO BIND SUCH ENTITY.
    type: business
  minimum_age:
    text: You must be at least 18 years old and have the legal capacity to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: No sensitive data uploads
    text: You agree not to upload or submit protected health information under HIPAA, government identification numbers, payment card numbers, or other categories of sensitive personal data to the Services, unless expressly permitted by an applicable Order and DPA.
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
name: Mutiny HQ
provenance_date: '2026-11-10'
provider_name: Mutiny HQ
provider_slug: mutiny-hq
slug: mutiny-hq-eligibility
source_date: '2026-11-10'
source_filename: mutiny-hq-eligibility.yml
source_heading: Eligibility
source_page: https://www.mutinyhq.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mutiny HQ\naid: mutiny-hq\nurl: https://www.mutinyhq.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have the legal capacity to form a binding contract.\n- type: business\n  text: IF CUSTOMER IS ACCEPTING ON BEHALF OF AN ENTITY, CUSTOMER REPRESENTS THAT CUSTOMER HAS THE AUTHORITY TO\n    BIND SUCH ENTITY.\nrestricted_uses:\n- summary: No sensitive data uploads\n  text: You agree not to upload or submit protected health information under HIPAA, government identification numbers,\n    payment\
  \ card numbers, or other categories of sensitive personal data to the Services, unless expressly permitted\n    by an applicable Order and DPA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have the legal capacity to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/mutiny-hq/eligibility/mutiny-hq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mutiny HQ's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Go-To-Market
- Sales Enablement
- Marketing
- Website Personalization
- Artificial Intelligence
- Agents
- MCP
- Account Based Marketing
- Content Generation
---
