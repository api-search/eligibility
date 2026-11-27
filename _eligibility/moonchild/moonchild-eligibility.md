---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: No illegal, harmful or infringing AI generation
    text: Generate content that is illegal, harmful, threatening, abusive, harassing, defamatory, or otherwise objectionable
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
name: Moonchild
provenance_date: '2026-11-10'
provider_name: Moonchild
provider_slug: moonchild
slug: moonchild-eligibility
source_date: '2026-11-10'
source_filename: moonchild-eligibility.yml
source_heading: Eligibility
source_page: https://moonchild.ai/terms_of_service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moonchild\naid: moonchild\nurl: https://moonchild.ai/terms_of_service.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Service.\nrestricted_uses:\n- summary: No illegal, harmful or infringing AI generation\n  text: Generate content that is illegal, harmful, threatening, abusive, harassing, defamatory, or otherwise objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age\
  \ to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/moonchild/eligibility/moonchild-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Moonchild's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Design
- Product
- Collaboration
- Automation
- Platform
---
