---
api_specs:
- filename: airweave-collections-api-openapi.yml
  format: yaml
  label: Airweave Collections API
  slug: airweave-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airweave/openapi/airweave-collections-api-openapi.yml
- filename: airweave-collections-search-api-openapi.yml
  format: yaml
  label: Airweave collections > search API
  slug: airweave-collections-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airweave/openapi/airweave-collections-search-api-openapi.yml
- filename: airweave-source-connections-api-openapi.yml
  format: yaml
  label: Airweave Source Connections API
  slug: airweave-source-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airweave/openapi/airweave-source-connections-api-openapi.yml
- filename: airweave-sources-api-openapi.yml
  format: yaml
  label: Airweave Sources API
  slug: airweave-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airweave/openapi/airweave-sources-api-openapi.yml
- filename: airweave-webhooks-api-openapi.yml
  format: yaml
  label: Airweave Webhooks API
  slug: airweave-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airweave/openapi/airweave-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, or a resident of, any country or on any list subject to comprehensive U.S. sanctions.
  entity_types:
  - text: You must be at least the age of majority in your jurisdiction and capable of forming a binding contract to use the Services.
    type: individual
  - text: If you are entering into these Terms on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least the age of majority in your jurisdiction and capable of forming a binding contract to use the Services.
    value: age of majority
  restricted_uses:
  - summary: Special categories or regulated data
    text: Use the Services to process special categories of personal data or regulated data (e.g., PHI, PCI, sensitive biometrics) unless expressly agreed in writing.
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
name: Airweave
provenance_date: '2026-11-09'
provider_name: Airweave
provider_slug: airweave
slug: airweave-eligibility
source_date: '2026-11-09'
source_filename: airweave-eligibility.yml
source_heading: Eligibility
source_page: https://airweave.ai/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airweave\naid: airweave\nurl: https://airweave.ai/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, or a resident of, any country or on any list subject to comprehensive\n    U.S. sanctions.\nentity_types:\n- type: individual\n  text: You must be at least the age of majority in your jurisdiction and capable of forming a binding contract\n    to use the Services.\n- type: business\n  text: If you are entering into these Terms on behalf of an organization, you represent that you have authority\n    to bind that organization.\n\
  restricted_uses:\n- summary: Special categories or regulated data\n  text: Use the Services to process special categories of personal data or regulated data (e.g., PHI, PCI, sensitive\n    biometrics) unless expressly agreed in writing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You must be at least the age of majority in your jurisdiction and capable of forming a binding contract\n    to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/airweave/eligibility/airweave-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Airweave's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Search
- RAG
- Retrieval
- Agents
- MCP
- Vector Search
- Data Integration
- Context
---
