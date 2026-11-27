---
api_specs:
- filename: bowmark-ai-library-api-openapi.yml
  format: yaml
  label: Bowmark AI Library API
  slug: bowmark-ai-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bowmark-ai/openapi/bowmark-ai-library-api-openapi.yml
- filename: bowmark-ai-recipes-api-openapi.yml
  format: yaml
  label: Bowmark AI Recipes API
  slug: bowmark-ai-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bowmark-ai/openapi/bowmark-ai-recipes-api-openapi.yml
- filename: bowmark-ai-run-api-openapi.yml
  format: yaml
  label: Bowmark AI Run API
  slug: bowmark-ai-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bowmark-ai/openapi/bowmark-ai-run-api-openapi.yml
- filename: bowmark-ai-scripts-api-openapi.yml
  format: yaml
  label: Bowmark AI Scripts API
  slug: bowmark-ai-scripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bowmark-ai/openapi/bowmark-ai-scripts-api-openapi.yml
- filename: bowmark-ai-sites-api-openapi.yml
  format: yaml
  label: Bowmark AI Sites API
  slug: bowmark-ai-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bowmark-ai/openapi/bowmark-ai-sites-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Where you use the Service other than for purposes of a business, certain provisions below are modified for you under Section 15 (Consumers)
    type: individual
  minimum_age:
    text: You must be at least the age of majority in your jurisdiction and capable of forming a binding contract.
    value: age of majority
  restricted_uses:
  - summary: Sanctioned persons or countries
    text: use the Service in violation of Canadian, United States, or other applicable export-control or sanctions laws, or on behalf of any person or in any country subject to those sanctions
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: We may, at any time, ask you to verify your identity, your organization, your payment method, or your intended use, and we may limit, pause, or refuse access until you do.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bowmark AI
provenance_date: '2026-11-09'
provider_name: Bowmark AI
provider_slug: bowmark-ai
slug: bowmark-ai-eligibility
source_date: '2026-11-09'
source_filename: bowmark-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bowmark.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bowmark AI\naid: bowmark-ai\nurl: https://bowmark.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Where you use the Service other than for purposes of a business, certain provisions below are modified for\n    you under Section 15 (Consumers)\nrestricted_uses:\n- summary: Sanctioned persons or countries\n  text: use the Service in violation of Canadian, United States, or other applicable export-control or sanctions\n    laws, or on behalf of any person or in any country subject to those sanctions\nverification:\n  kyc: true\n\
  \  kyb: true\n  approval_required: null\n  text: We may, at any time, ask you to verify your identity, your organization, your payment method, or your intended\n    use, and we may limit, pause, or refuse access until you do.\nminimum_age:\n  value: age of majority\n  text: You must be at least the age of majority in your jurisdiction and capable of forming a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/bowmark-ai/eligibility/bowmark-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bowmark AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Web
- Data Extraction
- Platform
- Company
---
