---
api_specs:
- filename: airops-agent-api-openapi.yml
  format: yaml
  label: AirOps Agent API
  slug: airops-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-agent-api-openapi.yml
- filename: airops-analytics-api-openapi.yml
  format: yaml
  label: AirOps Analytics API
  slug: airops-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-analytics-api-openapi.yml
- filename: airops-answers-api-openapi.yml
  format: yaml
  label: AirOps Answers API
  slug: airops-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-answers-api-openapi.yml
- filename: airops-apps-api-openapi.yml
  format: yaml
  label: AirOps Apps API
  slug: airops-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-apps-api-openapi.yml
- filename: airops-brand-kits-api-openapi.yml
  format: yaml
  label: AirOps Brand Kits API
  slug: airops-brand-kits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-brand-kits-api-openapi.yml
- filename: airops-citations-api-openapi.yml
  format: yaml
  label: AirOps Citations API
  slug: airops-citations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-citations-api-openapi.yml
- filename: airops-competitors-api-openapi.yml
  format: yaml
  label: AirOps Competitors API
  slug: airops-competitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-competitors-api-openapi.yml
- filename: airops-content-updates-api-openapi.yml
  format: yaml
  label: AirOps Content Updates API
  slug: airops-content-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-content-updates-api-openapi.yml
- filename: airops-executions-api-openapi.yml
  format: yaml
  label: AirOps Executions API
  slug: airops-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-executions-api-openapi.yml
- filename: airops-files-api-openapi.yml
  format: yaml
  label: AirOps Files API
  slug: airops-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-files-api-openapi.yml
- filename: airops-grids-api-openapi.yml
  format: yaml
  label: AirOps Grids API
  slug: airops-grids-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-grids-api-openapi.yml
- filename: airops-memory-stores-api-openapi.yml
  format: yaml
  label: AirOps Memory Stores API
  slug: airops-memory-stores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-memory-stores-api-openapi.yml
- filename: airops-personas-api-openapi.yml
  format: yaml
  label: AirOps Personas API
  slug: airops-personas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-personas-api-openapi.yml
- filename: airops-prompts-api-openapi.yml
  format: yaml
  label: AirOps Prompts API
  slug: airops-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-prompts-api-openapi.yml
- filename: airops-sentiment-theme-answers-api-openapi.yml
  format: yaml
  label: AirOps Sentiment Theme Answers API
  slug: airops-sentiment-theme-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-sentiment-theme-answers-api-openapi.yml
- filename: airops-tags-api-openapi.yml
  format: yaml
  label: AirOps Tags API
  slug: airops-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-tags-api-openapi.yml
- filename: airops-topics-api-openapi.yml
  format: yaml
  label: AirOps Topics API
  slug: airops-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-topics-api-openapi.yml
- filename: airops-web-pages-api-openapi.yml
  format: yaml
  label: AirOps Web Pages API
  slug: airops-web-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airops/openapi/airops-web-pages-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: either you, if you are an individual entering into the Agreement on your own behalf
    type: individual
  - text: the business entity or other organization on whose behalf you signed up is the Customer.
    type: business
  minimum_age:
    text: Customer must ensure that all Authorized Users are over 13 years old.
    value: '13'
  restricted_uses:
  - summary: Restricted Customer Content
    text: 'You agree not to submit any Customer Content, including but not limited to any User Content, that:'
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
name: AirOps
provenance_date: '2026-11-09'
provider_name: AirOps
provider_slug: airops
slug: airops-eligibility
source_date: '2026-11-09'
source_filename: airops-eligibility.yml
source_heading: Eligibility
source_page: https://www.airops.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AirOps\naid: airops\nurl: https://www.airops.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: either you, if you are an individual entering into the Agreement on your own behalf\n- type: business\n  text: the business entity or other organization on whose behalf you signed up is the Customer.\nrestricted_uses:\n- summary: Restricted Customer Content\n  text: 'You agree not to submit any Customer Content, including but not limited to any User Content, that:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '13'\n  text: Customer must ensure that all Authorized Users are over 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/airops/eligibility/airops-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AirOps's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Application
- Artificial Intelligence
- Content
- SEO
- Answer Engine Optimization
- Generative Engine Optimization
- Workflows
- MCP
- Analytics
- Agent Skills
- OpenAPI
- Knowledge Base
- Content Marketing
- Citations
---
