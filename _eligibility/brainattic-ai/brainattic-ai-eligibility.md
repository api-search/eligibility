---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is offered to organisations ("Customer", "you") and the individuals they authorise to use it
    type: business
  minimum_age:
    text: The Service is for business use by persons aged 18 or over
    value: '18'
  restricted_uses:
  - summary: No consumer or child use
    text: it is not offered to consumers or children
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
name: brainattic
provenance_date: '2026-11-09'
provider_name: brainattic
provider_slug: brainattic-ai
slug: brainattic-ai-eligibility
source_date: '2026-11-09'
source_filename: brainattic-ai-eligibility.yml
source_heading: Eligibility
source_page: https://brainattic.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: brainattic\naid: brainattic-ai\nurl: https://brainattic.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is offered to organisations (\"Customer\", \"you\") and the individuals they authorise to use it\nrestricted_uses:\n- summary: No consumer or child use\n  text: it is not offered to consumers or children\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is for business use by persons aged 18 or over\n"
source_yaml_url: https://artifacts.apis.io/brainattic-ai/eligibility/brainattic-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from brainattic's own page on 2026-11-09.
synthetic: false
tags:
- Knowledge Base
- Artificial Intelligence
- Enterprise
- Governance
- MCP
- Company
---
