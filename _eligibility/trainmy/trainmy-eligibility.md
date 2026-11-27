---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Services and access to the Site is void where prohibited.
  entity_types:
  - text: you may access and use the Site and Services for your personal or business use only
    type: business
  minimum_age:
    text: you are at least 18 years of age or, if higher, the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Not a substitute for AI legal compliance
    text: The Site and Services are not designated for the bypass or otherwise replacement of any external legal and regulatory requirements governing the usage of artificial intelligence (AI).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: C Sciences reserves the right to refuse to allow a user to download TrainMyAI, or to use any other service offered by C Sciences from time to time, for any reason
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TrainMyAI
provenance_date: '2026-11-10'
provider_name: TrainMyAI
provider_slug: trainmy
slug: trainmy-eligibility
source_date: '2026-11-10'
source_filename: trainmy-eligibility.yml
source_heading: Eligibility
source_page: https://trainmy.ai/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrainMyAI\naid: trainmy\nurl: https://trainmy.ai/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Services and access to the Site is void where prohibited.\nentity_types:\n- type: business\n  text: you may access and use the Site and Services for your personal or business use only\nrestricted_uses:\n- summary: Not a substitute for AI legal compliance\n  text: The Site and Services are not designated for the bypass or otherwise replacement of any external legal and\n    regulatory requirements governing the usage of artificial intelligence (AI).\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: C Sciences reserves the right to refuse to allow a user to download TrainMyAI, or to use any other service\n    offered by C Sciences from time to time, for any reason\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age or, if higher, the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/trainmy/eligibility/trainmy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from TrainMyAI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Chatbots
- RAG
- Platform
---
