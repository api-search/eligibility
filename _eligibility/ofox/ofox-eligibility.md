---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You confirm that you must be at least 18 years old to register an OfoxAI account, or your age must be sufficient to enter into a binding contract in your jurisdiction.
    type: individual
  - text: If you use OfoxAI services on behalf of an organization, you represent and warrant that you have the authority to bind that organization to this Agreement.
    type: business
  minimum_age:
    text: You confirm that you must be at least 18 years old to register an OfoxAI account, or your age must be sufficient to enter into a binding contract in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: You shall comply with applicable laws and regulations and shall not use OfoxAI services or accounts to engage in or facilitate any of the following conduct
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You agree that after registration, to better use the services and ensure account security, you shall complete real-name verification as prompted by OfoxAI; otherwise, you may be unable to use OfoxAI services or may be restricted during use.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NICE TALK
provenance_date: '2026-11-10'
provider_name: NICE TALK
provider_slug: ofox
slug: ofox-eligibility
source_date: '2026-11-10'
source_filename: ofox-eligibility.yml
source_heading: Eligibility
source_page: https://ofox.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NICE TALK\naid: ofox\nurl: https://ofox.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You confirm that you must be at least 18 years old to register an OfoxAI account, or your age must be sufficient\n    to enter into a binding contract in your jurisdiction.\n- type: business\n  text: If you use OfoxAI services on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization to this Agreement.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: You\
  \ shall comply with applicable laws and regulations and shall not use OfoxAI services or accounts to engage\n    in or facilitate any of the following conduct\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You agree that after registration, to better use the services and ensure account security, you shall complete\n    real-name verification as prompted by OfoxAI; otherwise, you may be unable to use OfoxAI services or may be\n    restricted during use.\nminimum_age:\n  value: '18'\n  text: You confirm that you must be at least 18 years old to register an OfoxAI account, or your age must be sufficient\n    to enter into a binding contract in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/ofox/eligibility/ofox-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from NICE TALK's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Platform
---
