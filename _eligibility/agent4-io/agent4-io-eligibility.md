---
api_specs:
- filename: agent4-io-api-openapi.json
  format: json
  label: chatagent-platform Api API
  slug: chatagent-platform-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent4-io/openapi/_original/agent4-io-api-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to enter into a contract.
    type: individual
  - text: Where you accept on behalf of an organisation, you confirm you are authorised to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 and able to enter into a contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful use or impersonation
    text: Use the service unlawfully, or to produce or distribute unlawful content;
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
name: Agent4.io
provenance_date: '2026-11-09'
provider_name: Agent4.io
provider_slug: agent4-io
slug: agent4-io-eligibility
source_date: '2026-11-09'
source_filename: agent4-io-eligibility.yml
source_heading: Eligibility
source_page: https://agent4.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agent4.io\naid: agent4-io\nurl: https://agent4.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to enter into a contract.\n- type: business\n  text: Where you accept on behalf of an organisation, you confirm you are authorised to bind it.\nrestricted_uses:\n- summary: Unlawful use or impersonation\n  text: Use the service unlawfully, or to produce or distribute unlawful content;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n \
  \ text: You must be at least 18 and able to enter into a contract.\n"
source_yaml_url: https://artifacts.apis.io/agent4-io/eligibility/agent4-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Agent4.io's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Customer Engagement
- Software-as-a-Service
- Agent Platform
---
