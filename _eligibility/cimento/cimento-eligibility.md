---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent and warrant that you have the right, authority, and capacity to enter into these terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: No competing products built from the Site
    text: you shall not access the Site in order to build a similar or competitive website, product, or service
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
name: Cimento
provenance_date: '2026-11-09'
provider_name: Cimento
provider_slug: cimento
slug: cimento-eligibility
source_date: '2026-11-09'
source_filename: cimento-eligibility.yml
source_heading: Eligibility
source_page: https://cimento.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cimento\naid: cimento\nurl: https://cimento.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you represent and warrant that you have the right, authority, and capacity to enter into these terms (on\n    behalf of yourself or the entity that you represent)\nrestricted_uses:\n- summary: No competing products built from the Site\n  text: you shall not access the Site in order to build a similar or competitive website, product, or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/cimento/eligibility/cimento-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cimento's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Phishing Simulation
- Human Risk Management
- Security
- Training
---
