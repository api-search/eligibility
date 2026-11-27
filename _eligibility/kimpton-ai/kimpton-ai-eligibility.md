---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms apply to all users of Kimpton, including individual subscribers and enterprise clients.
    type: individual
  - text: Kimpton offers paid pilots and enterprise plans with custom usage limits and commercial terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use Kimpton.
    value: '18'
  restricted_uses:
  - summary: Unlawful purpose
    text: Use Kimpton for any unlawful purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use Kimpton, you must create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kimpton AI
provenance_date: '2026-11-09'
provider_name: Kimpton AI
provider_slug: kimpton-ai
slug: kimpton-ai-eligibility
source_date: '2026-11-09'
source_filename: kimpton-ai-eligibility.yml
source_heading: Eligibility
source_page: https://kimpton.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kimpton AI\naid: kimpton-ai\nurl: https://kimpton.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These Terms apply to all users of Kimpton, including individual subscribers and enterprise clients.\n- type: business\n  text: Kimpton offers paid pilots and enterprise plans with custom usage limits and commercial terms.\nrestricted_uses:\n- summary: Unlawful purpose\n  text: Use Kimpton for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use Kimpton, you must create an account.\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use Kimpton.\n"
source_yaml_url: https://artifacts.apis.io/kimpton-ai/eligibility/kimpton-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Kimpton AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Investment Research
- Fintech
- Financial Services
- Portfolio Management
- Trade Analytics
- Research Automation
- Hedge Funds
---
