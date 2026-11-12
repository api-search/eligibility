---
api_specs:
- filename: comparr-fr-comparatifs-api-openapi.yml
  format: yaml
  label: Comparr Comparatifs API
  slug: comparr-fr-comparatifs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-comparatifs-api-openapi.yml
- filename: comparr-fr-deals-api-openapi.yml
  format: yaml
  label: Comparr Deals API
  slug: comparr-fr-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-deals-api-openapi.yml
- filename: comparr-fr-discovery-api-openapi.yml
  format: yaml
  label: Comparr Discovery API
  slug: comparr-fr-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-discovery-api-openapi.yml
- filename: comparr-fr-products-api-openapi.yml
  format: yaml
  label: Comparr Products API
  slug: comparr-fr-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-products-api-openapi.yml
- filename: comparr-fr-searches-api-openapi.yml
  format: yaml
  label: Comparr Searches API
  slug: comparr-fr-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-searches-api-openapi.yml
- filename: comparr-fr-versus-api-openapi.yml
  format: yaml
  label: Comparr Versus API
  slug: comparr-fr-versus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-versus-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Misleading or illegal form submissions
    text: envoyer par les formulaires (retours, propositions de produits, notations, alertes) des contenus illicites ou trompeurs
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
name: Comparr
provenance_date: '2026-11-09'
provider_name: Comparr
provider_slug: comparr-fr
slug: comparr-fr-eligibility
source_date: '2026-11-09'
source_filename: comparr-fr-eligibility.yml
source_heading: Eligibility
source_page: https://www.comparr.fr/conditions-utilisation
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Comparr\naid: comparr-fr\nurl: https://www.comparr.fr/conditions-utilisation\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Misleading or illegal form submissions\n  text: envoyer par les formulaires (retours, propositions de produits, notations, alertes) des contenus illicites\n    ou trompeurs\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/comparr-fr/eligibility/comparr-fr-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Comparr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Price Comparison
- E-Commerce
- Shopping
- Artificial Intelligence
- Product Reviews
- AI Agents
- MCP
- France
---
