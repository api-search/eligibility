---
api_specs:
- filename: canishop-ai-api-openapi.json
  format: json
  label: CanIShop API API
  slug: canishop-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canishop-ai/openapi/_original/canishop-ai-api-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No purchases or bypassing merchant restrictions
    text: Access to CanIShop does not authorize purchases, bypassing merchant restrictions, or actions on another person’s behalf.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration does not verify reports or authorize public sharing on a user’s behalf.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CanIShop
provenance_date: '2026-11-09'
provider_name: CanIShop
provider_slug: canishop-ai
slug: canishop-ai-eligibility
source_date: '2026-11-09'
source_filename: canishop-ai-eligibility.yml
source_heading: Eligibility
source_page: https://canishop.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CanIShop\naid: canishop-ai\nurl: https://canishop.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No purchases or bypassing merchant restrictions\n  text: Access to CanIShop does not authorize purchases, bypassing merchant restrictions, or actions on another\n    person’s behalf.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registration does not verify reports or authorize public sharing on a user’s behalf.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/canishop-ai/eligibility/canishop-ai-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from CanIShop's own page on 2026-11-09.
synthetic: false
tags:
- Checkout Reviews
- Agent Directory
- AI Agents
---
