---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are of legal age to form a binding contract.
    type: individual
  - text: If agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to do so and can bind that organization or entity to these Terms
    type: business
  minimum_age:
    text: Children under 18 should not attempt to register, use the Site or Services, or send personal information.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You will only use the Site in compliance with all applicable laws.
  - summary: Scraping, spamming, security violations
    text: '"Crawls," "scrapes," or "spiders" any page, data, or portion of or relating to the Site or Content (through use of manual or automated means)'
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
name: Norm Ai
provenance_date: '2026-11-10'
provider_name: Norm Ai
provider_slug: norm-ai
slug: norm-ai-eligibility
source_date: '2026-11-10'
source_filename: norm-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.norm.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Norm Ai\naid: norm-ai\nurl: https://www.norm.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are of legal age to form a binding contract.\n- type: business\n  text: If agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are\n    authorized to do so and can bind that organization or entity to these Terms\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You will only use the Site in compliance with all applicable laws.\n\
  - summary: Scraping, spamming, security violations\n  text: '\"Crawls,\" \"scrapes,\" or \"spiders\" any page, data, or portion of or relating to the Site or Content (through\n    use of manual or automated means)'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Children under 18 should not attempt to register, use the Site or Services, or send personal information.\n"
source_yaml_url: https://artifacts.apis.io/norm-ai/eligibility/norm-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Norm Ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Apps
- Legal
- Compliance
- AI Agents
- RegTech
- Governance
---
