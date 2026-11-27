---
api_specs:
- filename: mydentify-public-api-directories-api-openapi.yml
  format: yaml
  label: Mydentify Public API Directories API
  slug: mydentify-public-api-directories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mydentify-public-api/openapi/mydentify-public-api-directories-api-openapi.yml
- filename: mydentify-public-api-directories-json-api-openapi.yml
  format: yaml
  label: Mydentify Public API Directories.json API
  slug: mydentify-public-api-directories-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mydentify-public-api/openapi/mydentify-public-api-directories-json-api-openapi.yml
- filename: mydentify-public-api-imports-api-openapi.yml
  format: yaml
  label: Mydentify Public API Imports API
  slug: mydentify-public-api-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mydentify-public-api/openapi/mydentify-public-api-imports-api-openapi.yml
- filename: mydentify-public-api-leaderboards-api-openapi.yml
  format: yaml
  label: Mydentify Public API Leaderboards API
  slug: mydentify-public-api-leaderboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mydentify-public-api/openapi/mydentify-public-api-leaderboards-api-openapi.yml
- filename: mydentify-public-api-leaderboards-json-api-openapi.yml
  format: yaml
  label: Mydentify Public API Leaderboards.json API
  slug: mydentify-public-api-leaderboards-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mydentify-public-api/openapi/mydentify-public-api-leaderboards-json-api-openapi.yml
- filename: mydentify-public-api-product-categories-json-api-openapi.yml
  format: yaml
  label: Mydentify Public API Product Categories.json API
  slug: mydentify-public-api-product-categories-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mydentify-public-api/openapi/mydentify-public-api-product-categories-json-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 and legally able to enter this agreement.
    type: individual
  - text: If you use Mydentify for a company, you confirm that you can bind that company to these Terms.
    type: business
  minimum_age:
    text: You must be at least 13 and legally able to enter this agreement.
    value: '13'
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
name: Mydentify Public API
provenance_date: '2026-11-10'
provider_name: Mydentify Public API
provider_slug: mydentify-public-api
slug: mydentify-public-api-eligibility
source_date: '2026-11-10'
source_filename: mydentify-public-api-eligibility.yml
source_heading: Eligibility
source_page: https://mydentify.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mydentify Public API\naid: mydentify-public-api\nurl: https://mydentify.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 and legally able to enter this agreement.\n- type: business\n  text: If you use Mydentify for a company, you confirm that you can bind that company to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 and legally able to enter this agreement.\n"
source_yaml_url: https://artifacts.apis.io/mydentify-public-api/eligibility/mydentify-public-api-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Mydentify Public API's own page on 2026-11-10.
synthetic: false
tags:
- Product Discovery
- startup directories
- Leaderboards
- Research
- Software-as-a-Service
- Developer Tools
- Agent-Native
- Llms.txt
- Agent Skills
- Directories
---
