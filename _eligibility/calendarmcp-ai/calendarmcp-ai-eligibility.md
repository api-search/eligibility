---
api_specs:
- filename: calendarmcp-ai-openapi-generated.yml
  format: yaml
  label: CalendarMCP API
  slug: calendarmcp-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendarmcp-ai/openapi/_ae-authored/calendarmcp-ai-openapi-generated.yml
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
  - summary: Spam or unsolicited invitations
    text: Not use the service to send spam or unsolicited calendar invitations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Provide accurate and current information during registration
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CalendarMCP
provenance_date: '2026-11-09'
provider_name: CalendarMCP
provider_slug: calendarmcp-ai
slug: calendarmcp-ai-eligibility
source_date: '2026-11-09'
source_filename: calendarmcp-ai-eligibility.yml
source_heading: Eligibility
source_page: https://calendarmcp.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CalendarMCP\naid: calendarmcp-ai\nurl: https://calendarmcp.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spam or unsolicited invitations\n  text: Not use the service to send spam or unsolicited calendar invitations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Provide accurate and current information during registration\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/calendarmcp-ai/eligibility/calendarmcp-ai-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from CalendarMCP's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Artificial Intelligence
- MCP
- Google Calendar
- Integration
---
