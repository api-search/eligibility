---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: solely for your internal business operations or those of your Subscribing Entity
    type: business
  minimum_age:
    text: No part of the Service is directed to persons under the age of 16, and we do not knowingly collect personal information from persons under 16.
    value: '16'
  restricted_uses:
  - summary: Collecting credit card or login data
    text: Use the Service to collect credit card information or third parties' log-in credentials without permission
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right to approve or reject your application for a Subscription Plan in our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Octane AI
provenance_date: '2026-11-10'
provider_name: Octane AI
provider_slug: octane-ai
slug: octane-ai-eligibility
source_date: '2026-11-10'
source_filename: octane-ai-eligibility.yml
source_heading: Eligibility
source_page: https://octaneai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Octane AI\naid: octane-ai\nurl: https://octaneai.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: solely for your internal business operations or those of your Subscribing Entity\nrestricted_uses:\n- summary: Collecting credit card or login data\n  text: Use the Service to collect credit card information or third parties' log-in credentials without permission\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the right to approve or reject your application for a Subscription Plan in our sole\
  \ discretion.\nminimum_age:\n  value: '16'\n  text: No part of the Service is directed to persons under the age of 16, and we do not knowingly collect personal\n    information from persons under 16.\n"
source_yaml_url: https://artifacts.apis.io/octane-ai/eligibility/octane-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Octane AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Shopify
- E-Commerce
- Product Recommendations
- Quizzes
- Personalization
- Zero-Party Data
- Marketing
- Conversion Optimization
- Artificial Intelligence
---
