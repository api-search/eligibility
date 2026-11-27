---
api_specs:
- filename: ai-squared-catalogs-api-openapi.yml
  format: yaml
  label: AI Squared Catalogs API
  slug: ai-squared-catalogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-squared/openapi/ai-squared-catalogs-api-openapi.yml
- filename: ai-squared-connector-definitions-api-openapi.yml
  format: yaml
  label: AI Squared Connector Definitions API
  slug: ai-squared-connector-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-squared/openapi/ai-squared-connector-definitions-api-openapi.yml
- filename: ai-squared-connectors-api-openapi.yml
  format: yaml
  label: AI Squared Connectors API
  slug: ai-squared-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-squared/openapi/ai-squared-connectors-api-openapi.yml
- filename: ai-squared-models-api-openapi.yml
  format: yaml
  label: AI Squared Models API
  slug: ai-squared-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-squared/openapi/ai-squared-models-api-openapi.yml
- filename: ai-squared-syncrecords-api-openapi.yml
  format: yaml
  label: AI Squared Sync Records API
  slug: ai-squared-syncrecords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-squared/openapi/ai-squared-syncrecords-api-openapi.yml
- filename: ai-squared-syncrun-api-openapi.yml
  format: yaml
  label: AI Squared Sync Run API
  slug: ai-squared-syncrun-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-squared/openapi/ai-squared-syncrun-api-openapi.yml
- filename: ai-squared-syncruns-api-openapi.yml
  format: yaml
  label: AI Squared Sync Runs API
  slug: ai-squared-syncruns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-squared/openapi/ai-squared-syncruns-api-openapi.yml
- filename: ai-squared-syncs-api-openapi.yml
  format: yaml
  label: AI Squared Syncs API
  slug: ai-squared-syncs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-squared/openapi/ai-squared-syncs-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: You shall not permit your users to access or use any AI Squared Services in a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan, Syria or Crimea)
  entity_types:
  - text: If you are acting on behalf of an entity, you represent and warrant that you are authorized to bind that entity to these Terms
    type: business
  - text: otherwise, such terms refer to you as an individual
    type: individual
  - text: If Subscriber is a U.S. government entity, or this Agreement otherwise becomes subject to the Federal Acquisition Regulations (FAR)
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Hazardous or mission-critical uses
    text: use the AI Squared Services in hazardous or mission-critical circumstances or for uses requiring fail-safe performance
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AI Squared
provenance_date: '2026-11-09'
provider_name: AI Squared
provider_slug: ai-squared
slug: ai-squared-eligibility
source_date: '2026-11-09'
source_filename: ai-squared-eligibility.yml
source_heading: Eligibility
source_page: https://aisquared.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AI Squared\naid: ai-squared\nurl: https://aisquared.ai/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: You shall not permit your users to access or use any AI Squared Services in a U.S. embargoed country (currently\n    Cuba, Iran, North Korea, Sudan, Syria or Crimea)\nentity_types:\n- type: business\n  text: If you are acting on behalf of an entity, you represent and warrant that you are authorized to bind that\n    entity to these Terms\n- type: individual\n  text: otherwise, such terms refer to you as an\
  \ individual\n- type: government\n  text: If Subscriber is a U.S. government entity, or this Agreement otherwise becomes subject to the Federal Acquisition\n    Regulations (FAR)\nrestricted_uses:\n- summary: Hazardous or mission-critical uses\n  text: use the AI Squared Services in hazardous or mission-critical circumstances or for uses requiring fail-safe\n    performance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ai-squared/eligibility/ai-squared-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from AI Squared's own page on 2026-11-09.
synthetic: false
tags:
- Data Integration
- Reverse ETL
- Artificial Intelligence
- Machine Learning
- Customer Data Platform
- Data Activation
- Workflow Automation
- Open Source
- MCP
- Enterprise
- A2A
---
