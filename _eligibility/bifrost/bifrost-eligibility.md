---
api_specs:
- filename: bifrost-health-api-openapi.yml
  format: yaml
  label: Bifrost Health API
  slug: bifrost-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bifrost/openapi/bifrost-health-api-openapi.yml
- filename: bifrost-chat-completions-api-openapi.yml
  format: yaml
  label: Bifrost Chat Completions API
  slug: bifrost-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bifrost/openapi/bifrost-chat-completions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site and Services are intended solely for persons who are 18 or older.
    type: individual
  minimum_age:
    text: The Site and Services are intended solely for persons who are 18 or older.
    value: '18'
  restricted_uses:
  - summary: Unlawful use prohibited
    text: you warrant to Maxim that you will not use the Site for any purpose that is unlawful or prohibited by these Terms.
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
name: Bifrost
provenance_date: '2026-11-09'
provider_name: Bifrost
provider_slug: bifrost
slug: bifrost-eligibility
source_date: '2026-11-09'
source_filename: bifrost-eligibility.yml
source_heading: Eligibility
source_page: https://www.getmaxim.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bifrost\naid: bifrost\nurl: https://www.getmaxim.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site and Services are intended solely for persons who are 18 or older.\nrestricted_uses:\n- summary: Unlawful use prohibited\n  text: you warrant to Maxim that you will not use the Site for any purpose that is unlawful or prohibited by these\n    Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site and Services are intended solely\
  \ for persons who are 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/bifrost/eligibility/bifrost-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bifrost's own page on 2026-11-09.
synthetic: false
tags:
- AI Gateway
- LLM
- Load Balancing
- Open Source
- OpenAI-Compatible
- MCP
---
