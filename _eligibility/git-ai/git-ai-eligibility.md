---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'The Services are intended solely for business use. Customer represents that: (a) Customer is entering into this Agreement for business purposes and not for personal, family, or household purposes'
    type: business
  minimum_age:
    text: THE INDIVIDUAL ACCEPTING THIS AGREEMENT REPRESENTS THAT THEY ARE AT LEAST EIGHTEEN (18) YEARS OLD AND HAS THE AUTHORITY TO BIND CUSTOMER.
    value: '18'
  restricted_uses:
  - summary: Restricted regulated data
    text: Customer will not submit to the Services any data that is subject to heightened regulatory requirements, including Protected Health Information or other regulated health data, payment card data subject to PCI-DSS
  - summary: AI-specific prohibitions
    text: make legal, financial, employment, housing, healthcare, or other decisions that produce legal or similarly significant effects on individuals without meaningful human review
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
name: Git AI
provenance_date: '2026-11-09'
provider_name: Git AI
provider_slug: git-ai
slug: git-ai-eligibility
source_date: '2026-11-09'
source_filename: git-ai-eligibility.yml
source_heading: Eligibility
source_page: https://usegitai.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Git AI\naid: git-ai\nurl: https://usegitai.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'The Services are intended solely for business use. Customer represents that: (a) Customer is entering into\n    this Agreement for business purposes and not for personal, family, or household purposes'\nrestricted_uses:\n- summary: Restricted regulated data\n  text: Customer will not submit to the Services any data that is subject to heightened regulatory requirements,\n    including Protected Health Information or other regulated\
  \ health data, payment card data subject to PCI-DSS\n- summary: AI-specific prohibitions\n  text: make legal, financial, employment, housing, healthcare, or other decisions that produce legal or similarly\n    significant effects on individuals without meaningful human review\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: THE INDIVIDUAL ACCEPTING THIS AGREEMENT REPRESENTS THAT THEY ARE AT LEAST EIGHTEEN (18) YEARS OLD AND HAS\n    THE AUTHORITY TO BIND CUSTOMER.\n"
source_yaml_url: https://artifacts.apis.io/git-ai/eligibility/git-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Git AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Version Control
- DevOps
- Code Review
- Automation
---
