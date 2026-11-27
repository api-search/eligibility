---
api_specs:
- filename: agenthost-eu-openapi-generated.yml
  format: yaml
  label: agenthost API
  slug: agenthost-eu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenthost-eu/openapi/_ae-authored/agenthost-eu-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: agenthost is built for professional use.
    type: business
  - text: If you are acting as a consumer, mandatory Swedish consumer law applies to you regardless of anything in these terms
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use restrictions
    text: 'You may not use agenthost to: store, publish, or transmit anything unlawful'
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
name: agenthost
provenance_date: '2026-11-09'
provider_name: agenthost
provider_slug: agenthost-eu
slug: agenthost-eu-eligibility
source_date: '2026-11-09'
source_filename: agenthost-eu-eligibility.yml
source_heading: Eligibility
source_page: https://agenthost.eu/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: agenthost\naid: agenthost-eu\nurl: https://agenthost.eu/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: agenthost is built for professional use.\n- type: individual\n  text: If you are acting as a consumer, mandatory Swedish consumer law applies to you regardless of anything in\n    these terms\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: 'You may not use agenthost to: store, publish, or transmit anything unlawful'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agenthost-eu/eligibility/agenthost-eu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from agenthost's own page on 2026-11-09.
synthetic: false
tags:
- Web Hosting
- Artificial Intelligence
- MCP
- Cloud
- EU
---
