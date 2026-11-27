---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you use the Service on behalf of a company or other organisation, you confirm that you are authorised to bind it, and "you" means that organisation as well as you personally.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: submit, generate or distribute content that is unlawful, infringing, defamatory, harassing, hateful, sexually exploitative, or that violates another person's privacy
  - summary: Unqualified professional advice
    text: present AI outputs as professional advice to others without appropriate qualification and review
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
name: Bordet
provenance_date: '2026-11-09'
provider_name: Bordet
provider_slug: bordet-ai
slug: bordet-ai-eligibility
source_date: '2026-11-09'
source_filename: bordet-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.bordet.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bordet\naid: bordet-ai\nurl: https://www.bordet.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you use the Service on behalf of a company or other organisation, you confirm that you are authorised\n    to bind it, and \"you\" means that organisation as well as you personally.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: submit, generate or distribute content that is unlawful, infringing, defamatory, harassing, hateful,\
  \ sexually\n    exploitative, or that violates another person's privacy\n- summary: Unqualified professional advice\n  text: present AI outputs as professional advice to others without appropriate qualification and review\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/bordet-ai/eligibility/bordet-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Bordet's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Collaboration
- Multi-LLM
- Boardroom
- Productivity
- Company
---
