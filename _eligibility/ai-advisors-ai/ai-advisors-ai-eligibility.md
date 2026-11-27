---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old to use AI-Advisors.
    value: '16'
  restricted_uses:
  - summary: Unlawful use
    text: Use the platform to violate any laws or regulations
  - summary: Spam, harassment or harm
    text: Use the platform to spam, harass, or harm others
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
name: AI Advisors
provenance_date: '2026-11-09'
provider_name: AI Advisors
provider_slug: ai-advisors-ai
slug: ai-advisors-ai-eligibility
source_date: '2026-11-09'
source_filename: ai-advisors-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.ai-advisors.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AI Advisors\naid: ai-advisors-ai\nurl: https://www.ai-advisors.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: Use the platform to violate any laws or regulations\n- summary: Spam, harassment or harm\n  text: Use the platform to spam, harass, or harm others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use AI-Advisors.\n"
source_yaml_url: https://artifacts.apis.io/ai-advisors-ai/eligibility/ai-advisors-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AI Advisors's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- Software-as-a-Service
- Analytics
- Advertising
- Company
---
