---
api_specs:
- filename: whisper-online-a2a-api-openapi.yml
  format: yaml
  label: Whisper Security A2a API
  slug: whisper-online-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-a2a-api-openapi.yml
- filename: whisper-online-checkpoint-api-openapi.yml
  format: yaml
  label: Whisper Security Checkpoint API
  slug: whisper-online-checkpoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-checkpoint-api-openapi.yml
- filename: whisper-online-consistency-api-openapi.yml
  format: yaml
  label: Whisper Security Consistency API
  slug: whisper-online-consistency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-consistency-api-openapi.yml
- filename: whisper-online-inclusion-api-openapi.yml
  format: yaml
  label: Whisper Security Inclusion API
  slug: whisper-online-inclusion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-inclusion-api-openapi.yml
- filename: whisper-online-menu-api-openapi.yml
  format: yaml
  label: Whisper Security Menu API
  slug: whisper-online-menu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-menu-api-openapi.yml
- filename: whisper-online-query-api-openapi.yml
  format: yaml
  label: Whisper Security Query API
  slug: whisper-online-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-query-api-openapi.yml
- filename: whisper-online-tile-api-openapi.yml
  format: yaml
  label: Whisper Security Tile API
  slug: whisper-online-tile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-tile-api-openapi.yml
- filename: whisper-online-verify-identity-api-openapi.yml
  format: yaml
  label: Whisper Security Verify Identity API
  slug: whisper-online-verify-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-verify-identity-api-openapi.yml
- filename: whisper-online-well-known-api-openapi.yml
  format: yaml
  label: Whisper Security .well Known API
  slug: whisper-online-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-well-known-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept these Terms on behalf of an organization, you confirm you have authority to bind that organization
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Abuse and attacks
    text: attack, probe, or disrupt networks or systems you are not authorized to test
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
name: Whisper Security
provenance_date: '2026-11-10'
provider_name: Whisper Security
provider_slug: whisper-online
slug: whisper-online-eligibility
source_date: '2026-11-10'
source_filename: whisper-online-eligibility.yml
source_heading: Eligibility
source_page: https://whisper.online/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Whisper Security\naid: whisper-online\nurl: https://whisper.online/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept these Terms on behalf of an organization, you confirm you have authority to bind that organization\nrestricted_uses:\n- summary: Abuse and attacks\n  text: attack, probe, or disrupt networks or systems you are not authorized to test\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/whisper-online/eligibility/whisper-online-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Whisper Security's own page on 2026-11-10.
synthetic: false
tags:
- Agent Identity
- Agents
- IPv6
- DNS
- DNSSEC
- Threat Intelligence
- Security
- Egress
- A2A
- MCP
- RDAP
- Transparency Log
- Graph Database
- Agent-Native
- Netherlands
---
