---
api_specs:
- filename: voxplo-ai-agent-api-openapi.yml
  format: yaml
  label: Voxplo Agent API
  slug: voxplo-ai-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voxplo-ai/openapi/voxplo-ai-agent-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract to use the Service.
    type: individual
  - text: If you use the Service for an organisation, you confirm you have authority to accept these Terms on its behalf.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Robocalls and telephone spam
    text: send unsolicited automated calls (robocalls) or telephone spam
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
name: Voxplo
provenance_date: '2026-11-10'
provider_name: Voxplo
provider_slug: voxplo-ai
slug: voxplo-ai-eligibility
source_date: '2026-11-10'
source_filename: voxplo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.voxplo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Voxplo\naid: voxplo-ai\nurl: https://www.voxplo.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to use the Service.\n- type: business\n  text: If you use the Service for an organisation, you confirm you have authority to accept these Terms on its\n    behalf.\nrestricted_uses:\n- summary: Robocalls and telephone spam\n  text: send unsolicited automated calls (robocalls) or telephone spam\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/voxplo-ai/eligibility/voxplo-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Voxplo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice
- MCP
---
