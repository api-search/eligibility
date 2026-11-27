---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    - CA
    - AU
    - NZ
    text: Its data currently covers the US, UK, Canada, Australia and New Zealand; the service is available to people and AI assistants anywhere, including Southeast Asia and the Middle East.
  entity_types:
  - text: The service is available to people and AI assistants anywhere
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: false
    kyb: false
    kyc: false
    text: No account, sign-in, API key or payment is needed, and none is taken.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bankrolled.ai
provenance_date: '2026-11-09'
provider_name: Bankrolled.ai
provider_slug: bankrolled-ai
slug: bankrolled-ai-eligibility
source_date: '2026-11-09'
source_filename: bankrolled-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bankrolled.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bankrolled.ai\naid: bankrolled-ai\nurl: https://bankrolled.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  - CA\n  - AU\n  - NZ\n  excluded: []\n  text: Its data currently covers the US, UK, Canada, Australia and New Zealand; the service is available to people\n    and AI assistants anywhere, including Southeast Asia and the Middle East.\nentity_types:\n- type: individual\n  text: The service is available to people and AI assistants anywhere\nrestricted_uses: []\nverification:\n  kyc: false\n  kyb: false\n  approval_required: false\n  text: No account, sign-in, API key or payment\
  \ is needed, and none is taken.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bankrolled-ai/eligibility/bankrolled-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Bankrolled.ai's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Artificial Intelligence
- Deposit-Insurance
- Agents
- Regulatory
---
