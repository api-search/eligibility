---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You agree to use the Service only for lawful business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No access on behalf of competitors
    text: access the Service on behalf of a competitor of Clevra without our prior written permission
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
name: Clevra
provenance_date: '2026-11-09'
provider_name: Clevra
provider_slug: clevra-ai
slug: clevra-ai-eligibility
source_date: '2026-11-09'
source_filename: clevra-ai-eligibility.yml
source_heading: Eligibility
source_page: https://clevra.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clevra\naid: clevra-ai\nurl: https://clevra.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You agree to use the Service only for lawful business purposes\nrestricted_uses:\n- summary: No access on behalf of competitors\n  text: access the Service on behalf of a competitor of Clevra without our prior written permission\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clevra-ai/eligibility/clevra-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Clevra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Field Service Management
- Contractors
- Scheduling
- Invoicing
- Payments
- CRM
- MCP
- AI Assistants
---
