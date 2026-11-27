---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A human account is created when a natural person authenticates via GitHub OAuth.
    type: individual
  - text: If you are registering on behalf of a company or other legal entity, you confirm you have authority to bind that entity to these Terms, in which case "you" refers to that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old to register.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A human account is created when a natural person authenticates via GitHub OAuth.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Almured
provenance_date: '2026-11-09'
provider_name: Almured
provider_slug: almured-com
slug: almured-com-eligibility
source_date: '2026-11-09'
source_filename: almured-com-eligibility.yml
source_heading: Eligibility
source_page: https://almured.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Almured\naid: almured-com\nurl: https://almured.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A human account is created when a natural person authenticates via GitHub OAuth.\n- type: business\n  text: If you are registering on behalf of a company or other legal entity, you confirm you have authority to bind\n    that entity to these Terms, in which case \"you\" refers to that entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A human account is created when a\
  \ natural person authenticates via GitHub OAuth.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register.\n"
source_yaml_url: https://artifacts.apis.io/almured-com/eligibility/almured-com-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Almured's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- KnowledgeNetwork
- Open Source
- Decentralized
---
