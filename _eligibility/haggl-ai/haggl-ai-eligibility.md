---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a jurisdiction subject to applicable trade sanctions or export restrictions
  entity_types:
  - text: You are at least 18 years of age, or are using the Service on behalf of a business entity with authority to bind that entity
    type: individual
  - text: 'Vendors: Businesses that register for a haggl.ai account, install the embed, and configure negotiation parameters (ICP, pricing rules, discount thresholds).'
    type: business
  minimum_age:
    text: You are at least 18 years of age, or are using the Service on behalf of a business entity with authority to bind that entity
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: Use the Service for any unlawful purpose or in violation of any applicable law or regulation
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Vendors must register for an account to access the haggl.ai dashboard, obtain their embed code, and configure negotiation parameters.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: haggl-ai
provenance_date: '2026-11-09'
provider_name: haggl-ai
provider_slug: haggl-ai
slug: haggl-ai-eligibility
source_date: '2026-11-09'
source_filename: haggl-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.haggl.ai/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: haggl-ai\naid: haggl-ai\nurl: https://www.haggl.ai/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a jurisdiction subject to applicable trade sanctions or export restrictions\nentity_types:\n- type: individual\n  text: You are at least 18 years of age, or are using the Service on behalf of a business entity with authority\n    to bind that entity\n- type: business\n  text: 'Vendors: Businesses that register for a haggl.ai account, install the embed, and configure negotiation\n    parameters (ICP, pricing rules, discount thresholds).'\nrestricted_uses:\n\
  - summary: Unlawful use\n  text: Use the Service for any unlawful purpose or in violation of any applicable law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Vendors must register for an account to access the haggl.ai dashboard, obtain their embed code, and configure\n    negotiation parameters.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age, or are using the Service on behalf of a business entity with authority\n    to bind that entity\n"
source_yaml_url: https://artifacts.apis.io/haggl-ai/eligibility/haggl-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from haggl-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Commerce
- Negotiation
- Marketing
- Platform
---
