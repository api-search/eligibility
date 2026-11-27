---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use our Services. If you are between 13 and 18 (or the age of majority where you live), you may only use our Services under the supervision of a parent or legal guardian who agrees to be bound by these Terms.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use our Services.
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful content and conduct
    text: 'You agree not to use our Services to: Post, upload, or otherwise submit any User Content that: a. is defamatory, obscene, pornographic, vulgar, or offensive'
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
name: FlowGPT
provenance_date: '2026-11-09'
provider_name: FlowGPT
provider_slug: flowgpt
slug: flowgpt-eligibility
source_date: '2026-11-09'
source_filename: flowgpt-eligibility.yml
source_heading: Eligibility
source_page: https://flowgpt.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FlowGPT\naid: flowgpt\nurl: https://flowgpt.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use our Services. If you are between 13 and 18 (or the age of majority\n    where you live), you may only use our Services under the supervision of a parent or legal guardian who agrees\n    to be bound by these Terms.\nrestricted_uses:\n- summary: Unlawful or harmful content and conduct\n  text: 'You agree not to use our Services to: Post, upload, or otherwise submit any User Content that: a. is\
  \ defamatory,\n    obscene, pornographic, vulgar, or offensive'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/flowgpt/eligibility/flowgpt-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from FlowGPT's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Frontier Tech
- Artificial Intelligence
- Generative AI
- Chatbots
- Prompt Engineering
- LLM
- Community Platform
---
