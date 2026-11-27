---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to create an account
    type: individual
  minimum_age:
    text: You must be at least 16 years old to create an account
    value: '16'
  restricted_uses:
  - summary: Unlawful or malicious use
    text: Use the Service for any unlawful purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must verify your email address via OTP before accessing the API
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: crowvault-ai
provenance_date: '2026-11-09'
provider_name: crowvault-ai
provider_slug: crowvault-ai
slug: crowvault-ai-eligibility
source_date: '2026-11-09'
source_filename: crowvault-ai-eligibility.yml
source_heading: Eligibility
source_page: https://crowvault.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: crowvault-ai\naid: crowvault-ai\nurl: https://crowvault.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to create an account\nrestricted_uses:\n- summary: Unlawful or malicious use\n  text: Use the Service for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must verify your email address via OTP before accessing the API\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to create an account\n"
source_yaml_url: https://artifacts.apis.io/crowvault-ai/eligibility/crowvault-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from crowvault-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Developer Tools
- Automation
- Cloud
- Platform
---
