---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract to use Caybl.ai.
    type: individual
  - text: If you use Caybl.ai on behalf of a company or other organization, you confirm you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use Caybl.ai.
    value: '18'
  restricted_uses:
  - summary: Unlawful or policy-violating use
    text: Use Caybl.ai for any unlawful purpose or in violation of Google's API Services User Data Policy, the Google Ads API Terms of Service, the Reddit Ads API Terms, or any third-party AI agent's own terms.
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
name: Caybl.ai
provenance_date: '2026-11-09'
provider_name: Caybl.ai
provider_slug: caybl-ai
slug: caybl-ai-eligibility
source_date: '2026-11-09'
source_filename: caybl-ai-eligibility.yml
source_heading: Eligibility
source_page: https://caybl.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Caybl.ai\naid: caybl-ai\nurl: https://caybl.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to use Caybl.ai.\n- type: business\n  text: If you use Caybl.ai on behalf of a company or other organization, you confirm you have authority to bind\n    that organization to these Terms.\nrestricted_uses:\n- summary: Unlawful or policy-violating use\n  text: Use Caybl.ai for any unlawful purpose or in violation of Google's API Services User Data Policy, the Google\n\
  \    Ads API Terms of Service, the Reddit Ads API Terms, or any third-party AI agent's own terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract to use Caybl.ai.\n"
source_yaml_url: https://artifacts.apis.io/caybl-ai/eligibility/caybl-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Caybl.ai's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Artificial Intelligence
- Marketing
- MCP
- Google
---
