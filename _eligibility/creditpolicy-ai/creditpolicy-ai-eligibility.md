---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing on behalf of a company, brokerage, aggregator or other entity, you represent that you have authority to bind that entity
    type: business
  minimum_age:
    text: To use the Service you must be at least 18
    value: '18'
  restricted_uses:
  - summary: No consumer-facing automated credit decisioning
    text: use the Service for any consumer-facing automated credit decisioning
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We may accept or decline any registration, trial or subscription request in our discretion, and will tell you if we do.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CreditPolicy.ai
provenance_date: '2026-11-09'
provider_name: CreditPolicy.ai
provider_slug: creditpolicy-ai
slug: creditpolicy-ai-eligibility
source_date: '2026-11-09'
source_filename: creditpolicy-ai-eligibility.yml
source_heading: Eligibility
source_page: https://creditpolicy.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CreditPolicy.ai\naid: creditpolicy-ai\nurl: https://creditpolicy.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing on behalf of a company, brokerage, aggregator or other entity, you represent that you\n    have authority to bind that entity\nrestricted_uses:\n- summary: No consumer-facing automated credit decisioning\n  text: use the Service for any consumer-facing automated credit decisioning\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We may accept or decline any registration,\
  \ trial or subscription request in our discretion, and will tell\n    you if we do.\nminimum_age:\n  value: '18'\n  text: To use the Service you must be at least 18\n"
source_yaml_url: https://artifacts.apis.io/creditpolicy-ai/eligibility/creditpolicy-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from CreditPolicy.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Credit Policy
- Lending
- Mortgage Brokers
- MCP
- Financial Services
- Australia
---
