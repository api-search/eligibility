---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering as a business entity, you personally guarantee that you have the authority to agree to the Terms on behalf of the business.
    type: business
  - text: If you are an individual (such as an independent leasing agent), these Terms apply to you in your individual capacity.
    type: individual
  minimum_age:
    text: You must be 18 years or older to use the Grotto Platform.
    value: '18'
  restricted_uses:
  - summary: Recording consent obligations
    text: 'You acknowledge and agree that you are solely responsible for: (a) determining and complying with all applicable federal, state, and local laws, rules, and regulations governing the recording, monitoring, and interception of communications'
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
name: Grotto AI
provenance_date: '2026-11-09'
provider_name: Grotto AI
provider_slug: grotto-ai
slug: grotto-ai-eligibility
source_date: '2026-11-09'
source_filename: grotto-ai-eligibility.yml
source_heading: Eligibility
source_page: https://grotto.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Grotto AI\naid: grotto-ai\nurl: https://grotto.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering as a business entity, you personally guarantee that you have the authority to agree\n    to the Terms on behalf of the business.\n- type: individual\n  text: If you are an individual (such as an independent leasing agent), these Terms apply to you in your individual\n    capacity.\nrestricted_uses:\n- summary: Recording consent obligations\n  text: 'You acknowledge and agree\
  \ that you are solely responsible for: (a) determining and complying with all applicable\n    federal, state, and local laws, rules, and regulations governing the recording, monitoring, and interception\n    of communications'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older to use the Grotto Platform.\n"
source_yaml_url: https://artifacts.apis.io/grotto-ai/eligibility/grotto-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Grotto AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Multifamily
- Leasing
- Sales Coaching
- PropTech
- Real Estate
- Conversation Intelligence
- Machine Learning
- Natural Language Processing
- Image Analysis
- DataInsights
---
