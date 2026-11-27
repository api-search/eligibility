---
api_specs:
- filename: alpic-analytics-api-openapi.yml
  format: yaml
  label: Alpic Analytics API
  slug: alpic-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-analytics-api-openapi.yml
- filename: alpic-beacon-api-openapi.yml
  format: yaml
  label: Alpic Beacon API
  slug: alpic-beacon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-beacon-api-openapi.yml
- filename: alpic-deployments-api-openapi.yml
  format: yaml
  label: Alpic Deployments API
  slug: alpic-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-deployments-api-openapi.yml
- filename: alpic-distribution-api-openapi.yml
  format: yaml
  label: Alpic Distribution API
  slug: alpic-distribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-distribution-api-openapi.yml
- filename: alpic-environments-api-openapi.yml
  format: yaml
  label: Alpic Environments API
  slug: alpic-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-environments-api-openapi.yml
- filename: alpic-projects-api-openapi.yml
  format: yaml
  label: Alpic Projects API
  slug: alpic-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-projects-api-openapi.yml
- filename: alpic-teams-api-openapi.yml
  format: yaml
  label: Alpic Teams API
  slug: alpic-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-teams-api-openapi.yml
- filename: alpic-tunnels-api-openapi.yml
  format: yaml
  label: Alpic Tunnels API
  slug: alpic-tunnels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-tunnels-api-openapi.yml
- filename: alpic-insights-api-openapi.yml
  format: yaml
  label: Alpic Insights API
  slug: alpic-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-insights-api-openapi.yml
- filename: alpic-submissions-api-openapi.yml
  format: yaml
  label: Alpic Submissions API
  slug: alpic-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-submissions-api-openapi.yml
- filename: alpic-telemetry-api-openapi.yml
  format: yaml
  label: Alpic Telemetry API
  slug: alpic-telemetry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-telemetry-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Customer must be at least 18 years old (or the age of majority in its jurisdiction).
    type: individual
  - text: if you, accept this Agreement on behalf of a company or other legal entity, you represent and warrant that you are duly authorized to bind that entity as the Customer.
    type: business
  minimum_age:
    text: The Customer must be at least 18 years old (or the age of majority in its jurisdiction).
    value: '18'
  restricted_uses:
  - summary: Free Plan limited to non-production use
    text: the Free Plan is provided for testing, evaluation, and non-production use and is not designed for business-critical or production workloads.
  - summary: Export restrictions
    text: The Customer shall not export, re-export, transfer, or enable the use of the Services in any U.S.-embargoed country or in violation of any applicable U.S. export law or regulation.
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
name: Alpic
provenance_date: '2026-11-09'
provider_name: Alpic
provider_slug: alpic
slug: alpic-eligibility
source_date: '2026-11-09'
source_filename: alpic-eligibility.yml
source_heading: Eligibility
source_page: https://alpic.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alpic\naid: alpic\nurl: https://alpic.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Customer must be at least 18 years old (or the age of majority in its jurisdiction).\n- type: business\n  text: if you, accept this Agreement on behalf of a company or other legal entity, you represent and warrant that\n    you are duly authorized to bind that entity as the Customer.\nrestricted_uses:\n- summary: Free Plan limited to non-production use\n  text: the Free Plan is provided for testing, evaluation, and non-production\
  \ use and is not designed for business-critical\n    or production workloads.\n- summary: Export restrictions\n  text: The Customer shall not export, re-export, transfer, or enable the use of the Services in any U.S.-embargoed\n    country or in violation of any applicable U.S. export law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Customer must be at least 18 years old (or the age of majority in its jurisdiction).\n"
source_yaml_url: https://artifacts.apis.io/alpic/eligibility/alpic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Alpic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Cloud Platform
- Developer Tools
- Deployment
- ChatGPT Apps
- AI Agents
- Platform-as-a-Service
---
