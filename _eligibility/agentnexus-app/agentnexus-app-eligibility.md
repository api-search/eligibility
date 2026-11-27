---
api_specs:
- filename: agentnexus-app-discovery-api-openapi.yml
  format: yaml
  label: Agent Nexus Discovery API
  slug: agentnexus-app-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentnexus-app/openapi/agentnexus-app-discovery-api-openapi.yml
- filename: agentnexus-app-keys-api-openapi.yml
  format: yaml
  label: Agent Nexus Keys API
  slug: agentnexus-app-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentnexus-app/openapi/agentnexus-app-keys-api-openapi.yml
- filename: agentnexus-app-registry-api-openapi.yml
  format: yaml
  label: Agent Nexus Registry API
  slug: agentnexus-app-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentnexus-app/openapi/agentnexus-app-registry-api-openapi.yml
- filename: agentnexus-app-reliability-api-openapi.yml
  format: yaml
  label: Agent Nexus Reliability API
  slug: agentnexus-app-reliability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentnexus-app/openapi/agentnexus-app-reliability-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use it as an individual, you confirm you are of legal age in your jurisdiction.
    type: individual
  - text: If you use the Service on behalf of an organisation, you confirm you have authority to bind that organisation.
    type: business
  minimum_age:
    text: you are of legal age in your jurisdiction
    value: null
  restricted_uses:
  - summary: Unlawful, fraudulent or deceptive use
    text: use it for unlawful purposes, fraud, spam or deceptive activity
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
name: Agent Nexus
provenance_date: '2026-11-09'
provider_name: Agent Nexus
provider_slug: agentnexus-app
slug: agentnexus-app-eligibility
source_date: '2026-11-09'
source_filename: agentnexus-app-eligibility.yml
source_heading: Eligibility
source_page: https://agentnexus.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agent Nexus\naid: agentnexus-app\nurl: https://agentnexus.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you use it as an individual, you confirm you are of legal age in your jurisdiction.\n- type: business\n  text: If you use the Service on behalf of an organisation, you confirm you have authority to bind that organisation.\nrestricted_uses:\n- summary: Unlawful, fraudulent or deceptive use\n  text: use it for unlawful purposes, fraud, spam or deceptive activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/agentnexus-app/eligibility/agentnexus-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Agent Nexus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Infrastructure
- Registry
- Agents
- Platform
---
